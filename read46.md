# Inheritance and Interfaces

- **Class** − A class can be defined as a template/blueprint that describes the behavior/state that the object of its type supports.
- **Object** − Objects have states and behaviors. Example: A car has states - color, module, manufacturing year as well as behavior such as acceleration, braking . An object is an instance of a class.


## Inheritance :-

* Inheritance in Java is a mechanism in which one object acquires all the properties and behaviors of a parent object. It is an important part of OOPs (Object Oriented programming system).

* The idea behind inheritance in Java is that you can create new classes that are built upon existing classes. When you inherit from an existing class, you can reuse methods and fields of the parent class. Moreover, you can add new methods and fields in your current class also.

## Why use inheritance in java:-
* For Method Overriding.
* For Code Reusability.

## Terms used in Inheritance:-

* **Class:** A class is a group of objects which have common properties. It is a template or blueprint from which objects are created.
* **Sub Class/Child Class:** Subclass is a class which inherits the other class. It is also called a derived class, extended class, or child class.
* **Super Class/Parent Class:** Superclass is the class from where a subclass inherits the features. It is also called a base class or a parent class.
* **Reusability:** As the name specifies, reusability is a mechanism which facilitates you to reuse the fields and methods of the existing class when you create a new class.


## Interface in Java :-
* An interface in Java is a blueprint of a class. It has static constants and abstract methods.
* you can say that interfaces can have abstract methods and variables. It cannot have a method body.

## Java Interface Example :-
//Interface declaration: by first user  
interface Drawable{  
void draw();  
}  
//Implementation: by second user  
class Rectangle implements Drawable{  
public void draw(){System.out.println("drawing rectangle");}  
}  
class Circle implements Drawable{  
public void draw(){System.out.println("drawing circle");}  
}  
//Using interface: by third user  
class TestInterface1{  
public static void main(String args[]){  
Drawable d=new Circle(); 
d.draw();  
}}  