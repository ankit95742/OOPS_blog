# OOPS Concepts in JAVA

Object Oriented Concepts are very important. Withput having an idea about OOPS concepts, you will not able to design systems in the object-oriented programming model. It simplifies software development and maintenance.

The core OOPs concepts:
1. Object
2. Class
3. Abstraction
4. Encapsulation
5. Inheritance
6. Polymorphism

Let's discuss above each OOPS concepts with a real-world example.

## 1. Object

**Object** is an instance of a class. An object in OOPS is nothing but a self-contained component which consists of methods and properties to make a particular type of data useful. For example color name, table, bag, barking. When you send a message to an object, you are asking the object to invoke or execute one of its methods as defined in the class.

For real world example like Chair, Bike, Marker, Car, Books etc. It can be pysical or logical. 
Bicycles have properties (like cuurent gear, current pedal cadence, current speed) and behavior (changing gear, changing pedal cadence, applying brakes).

Object Systax in Java
```
ClassName ReferenceVariable = new ClassName();
```

## 2. Class

 a **class** is a blueprint for creating objects (a particular data structure), providing initial values for state (member variables or attributes), and implementations of behavior (member functions or methods).The class that contains the main method of Java program represent the entrire program. A class proviedes a special type of methods knowns as constructors which are invoked to construct objects from the class.
 
 A class declaration consists of:
 
 1. Modifiers: Can be public or default access.
 2. Class name: Initial letter.
 3.  Superclass: A class can only extend (subclass) one parent.
 4. Interfaces: A class can implement more than one interface.
 5. Body: Body surrounded by braces, { }.
 
```
class class_name{
    class_body
}
```

## 3. Abstraction

**Abstraction** means hiding lower-level details and exposing only the essential and relevant details to the users.

The first example, let's consider a Car, which abstract the internal deatails and exposes to the driver only those detail that are relevant to the interaction of the driver with the car.

The second example, consider an ATM Machine; All are performing operations on the ATM machine like cash withdrawal, money transfer, retrieve mini-statement...etc. but we can't know internal details about ATM.

If we want make class abstract we use abstract keyword for that and that class can not be instantiated directly. We define a method as abstract and implement this method in subclass.

![This is an image](https://media.geeksforgeeks.org/wp-content/uploads/Abstract-classes-and-methods-Page-1.png)

## 4. Encapsulation

**Encapsulation** is a process of wrapping of data and methods in a single unit is called encapsulation.

In OOP, data and methods operating on that data are combined together to form a single unit, which is referred to as a Class. Java bean is fully encapsulated class because all the data members are private here. Encapsulation is implemented using private, package-private and protected access modifiers. Encapsulation solves the problem in the implementation level.

![Image](https://usemynotes.com/wp-content/uploads/2021/06/encapsulation-in-java.jpg)

## 5. Inheritance

The **Inheritance** is process of obtaining the data members and methods from one class to another class, plus can have its own is knons as inhertance. It is one of the fundamental features of OOP.

Inheritance represents the IS-A relationship which is also known as a parent-child relationship. Its use for code reusability and for method overriding.

```
class Subclass-name extends Superclass-name  
{  
   //methods and fields  
}
```
Type of Inheritance in Java
1. Single Inheritance
2. Multilevel Inheritance
3. Hierach

 
 
 
 



