## Experiment1a:
## Title:Primitive data types
```java
class PrimitiveDataTypes{
  byte b;
  int i;
  float f;
  char c;
  double d;
  long l;
  boolean bool;
  short s;
public static void main(String[] args){
  PrimitiveDataTypes obj = new PrimitiveDataTypes();
  System.out.println("default value of int:"+obj.i);
  System.out.println("default value of float:"+obj.f);
  System.out.println("default value of char:"+obj.c);
  System.out.println("default value of double:"+obj.d);
  System.out.println("default value of long:"+obj.l);
  System.out.println("default value of boolean:"+obj.bool);
  System.out.println("default value of short:"+obj.s);
  System.out.println("default value of byte:"+obj.b);
  }
}

```

## OUTPUT:

![output](experiment1a.png)



## Experiment1b:
## Title:Quadratic equation
```java
import java.util.Scanner;
class QuadraticEquation{
  public static void main(String[] args){
    double a,b,c,D;
    Scanner input=new Scanner(System.in);
    System.out.println("Enter the a value:");
    a=input.nextDouble();
    System.out.println("Enter the b value:");
    b=input.nextDouble();
    System.out.println("Enter the c value:");
    c=input.nextDouble();
    D=b*b-4*a*c;
    System.out.println("Discriminant is:"+D);
    if(D>0){
      System.out.println("ROOTS ARE REAL AND DISTICT");
      double root1=(-b+Math.sqrt(D))/(2*a);
      double root2=(-b-Math.sqrt(D))/(2*a);
      System.out.println("Root1 is: "+root1);
      System.out.println("Root2 is:"+root2);
      }
    else if(D==0){
      double root=-b/2*a;
      System.out.println("ROOTS ARE REAL AND EQUAL");
      System.out.println("ROOT IS:"+root);
    }
    else {
      System.out.println("ROOTS ARE COMPLEX AND IMAGINARY");
      double real=-b/2*a;
      double img=(Math.sqrt(-D))/2*a;
      System.out.println("Root1:"+real+"+i"+img);
      System.out.println("Root2:"+real+"-i"+img);
    }
  input.close();
  }
}

```
## OUTPUT:

![output](experiment1b.png)


