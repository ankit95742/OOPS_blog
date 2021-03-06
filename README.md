# OOPS Concepts in JAVA

Object-Oriented Concepts are very important. Without having an idea about OOPS concepts, you will not able to design systems in the object-oriented programming model. It simplifies software development and maintenance.

The core OOPs concepts:
1. Object
2. Class
3. Abstraction
4. Encapsulation
5. Inheritance
6. Polymorphism

Let's discuss above each OOPS concept with a real-world example.

## 1. Object

**Object** is an instance of a class. An object in OOPS is nothing but a self-contained component that consists of methods and properties to make a particular type of data useful. For example color name, table, bag, barking. When you send a message to an object, you are asking the object to invoke or execute one of its methods as defined in the class.

For real-world examples like Chair, Bike, Marker, Car, Books, etc. It can be physical or logical. 
Bicycles have properties (like current gear, current pedal cadence, current speed) and behavior (changing gear, changing pedal cadence, applying brakes).

Object Syntax in Java
```
ClassName ReferenceVariable = new ClassName();
```

## 2. Class

 a **class** is a blueprint for creating objects (a particular data structure), providing initial values for state (member variables or attributes), and implementations of behavior (member functions or methods). The class that contains the main method of the Java program represents the entire program. A class provides a special type of methods knowns as constructors which are invoked to construct objects from the class.
 
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

The first example, let's consider a Car, which abstracts the internal details and exposes to the driver only those detail that is relevant to the interaction of the driver with the car.

The second example, consider an ATM Machine; All are performing operations on the ATM-like cash withdrawal, money transfer, retrieve mini-statement...etc. but we can't know internal details about ATM.

If we want to make a class abstract we use an abstract keyword for that and that class can not be instantiated directly. We define a method as abstract and implement this method in a subclass.

![This is an image](https://media.geeksforgeeks.org/wp-content/uploads/Abstract-classes-and-methods-Page-1.png)

## 4. Encapsulation

**Encapsulation** is a process of wrapping data and methods in a single unit is called encapsulation.

In OOP, data and methods operating on that data are combined to form a single unit, which is referred to as a Class. Java bean is a fully encapsulated class because all the data members are private here. Encapsulation is implemented using private, package-private, and protected access modifiers. Encapsulation solves the problem at the implementation level.

![Image](https://usemynotes.com/wp-content/uploads/2021/06/encapsulation-in-java.jpg)

## 5. Inheritance

The **Inheritance** is the process of obtaining the data members and methods from one class to another class, plus can have its own is known as inheritance. It is one of the fundamental features of OOP.

Inheritance represents the IS-A relationship which is also known as a parent-child relationship. It's used for code reusability and method overriding.

Super Class: The class whose features are inherited is known as a superclass (or a base class or a parent class).
Sub Class: The class that inherits the other class is known as a subclass(or a derived class, extended class, or child class). The subclass can add its fields and methods in addition to the superclass fields and methods.

```
class Subclass-name extends Superclass-name  
{  
   //methods and fields  
}
```
Type of Inheritance in Java
1. Single Inheritance
2. Multilevel Inheritance
3. Hierarchical Inheritance
4. Multiple Inheritance(Theogh Interface)

![Image](https://static.javatpoint.com/images/core/typesofinheritance.jpg)

## 6. Polymorphism

**Polymorphism** is the ability of an object to take on many forms. The most common use of polymorphism is OOPS occurs when a parent class reference is used to refer to a child class object. The process of representing one form in multiple forms is known as polymorphism.

for example suppose if you are in a classroom that time you behave like a student, when you are in the market at that time you behave like a customer, Here one person present in different-different behaviors.

Types of Polymorphism in Java

1. Compile time polymorphism or method overloading

If the class contains two or more methods having the same name and different arguments then it is method overloading.

2. Runtime polymorphism or method overriding

Runtime polymorphism is a process in which a call to an overridden method is resolved at runtime rather than compile-time.

![Image](https://csharpcorner-mindcrackerinc.netdna-ssl.com/article/method-overloading-and-method-overriding/Images/Difference.png)
