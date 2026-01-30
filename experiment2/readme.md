
## Experiment2a:

## Title:Myclass

```java
class MyClass{
void display(){
System.out.println("This Is Java");
}
int calculation(int a,int b){
return a+b;
}
public static void  main(String[] args){
MyClass obj = new MyClass();
obj.display();
int result = obj.calculation(10,20);
System.out.println("Addition of 2 num is:"+result);
}
}

```
## OUTPUT:




![output](2a.png)




## Experiment2b:

## Title:OverloadExample


```java
class OverloadExample{
int add(int a, int b){
return a+b;
}
double add(double a,double b){
return a+b;
}
int add(int a, int b, int c){
return a+b+c;
}
public static void main(String[] args){
OverloadExample obj = new OverloadExample();
System.out.println("Result of adding 2 integers:"+obj.add(10,20));
System.out.println("Result of adding 2 doubles:"+obj.add(10.0,20.0));
System.out.println("Result of adding 3 integers:"+obj.add(10,20,30));
}
}

```

## OUTPUT:



![output](2b.png)



## Experimnet2c:
## Title:Constructor


```java
class Student{
String name;
int age;
int marks;
Student(String s,int a, int m){
name = s;
age = a;
marks = m;
}
void display(){
System.out.println("NAME:"+name);
System.out.println("AGE:"+age);
System.out.println("MARKS:"+marks);
}
public static void main(String[] args){
Student s1 = new Student("Alice",20,85);
s1.display();
}
}
```
## OUTPUT:



![output](2c.png)
