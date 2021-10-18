# Inheritance and Interfaces

- **Class** − A class can be defined as a template/blueprint that describes the behavior/state that the object of its type supports.
* class declarations can include: Modifiers such as (public, private,protacted), class name,class body (that contain the template of the properties and methods).

- **Object** − Objects have states and behaviors. Example: A car has states - color, module, manufacturing year as well as behavior such as acceleration, braking . An object is an instance of a class(we are using the constructor to create a new instance of the class that named obj).


## Inheritance :-
* Object-oriented programing allows classes(sub class) to inherit proparties(state) and behavior(methode) from other classes(super class) and after inherit we can add for every (sub class) his own proparties and methodes withe the ability to use the extended (proparties and methodes) by the sub clASSS .
* this make our code reusable and stronger .

* there is a type of class named abstract class that we can extend from it but we can't constract an object using the same class .
## Terms used in Inheritance:-

* **Class:** : as we define in the class section above .
* **Sub Class/Child Class:** is the class that take his properties and methods from another class (super class) and after that itcan add his own properties and methods.
* **Super Class/Parent Class:**subclass inherits properties and methods from this class (super class).


## Interface in Java :- 
* An interface in Java is a blueprint of a class.that contain just constants varablies , static methods and  method signatures but without the body of the method.
* you can say that interfaces can have abstract methods and constants variables.

## Java Interface Example :-
//Interface declaration: by first user  
interface Drawable{  
void draw();          // just contain the name of the method without the body of it .
}  
//Implementation: by second user  
class Rectangle implements Drawable{  
public void draw(){System.out.println("drawing rectangle");}    // her after implementation we add the body of the method .
}  
class Circle implements Drawable{  
public void draw(){System.out.println("drawing circle");}  // her after implementation we add the same body of the method but with different implementation.
}  
//Using interface: by third user  
class TestInterface1{  
public static void main(String args[]){  
Drawable d=new Circle(); 
d.draw();  
}}  