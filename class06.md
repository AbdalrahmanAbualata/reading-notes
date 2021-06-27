# JS
## Understanding The Problem Domain Is The Hardest Part Of Programming :
* The single hardest thing about programming is learning the problem domain, Programming is easy if you understand the problem domain .
* **What is the hardest thing about writing code?**
- here are many common answers to this question:

     * Learning a new technology
     *  Naming things
     *  Testing your code
     *  Debugging
    * Fixing bugs
     * Making software maintainable
### What can you do about it?
* If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

     * Make the problem domain easier
     * Get better at understanding the problem domain
* You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.

## Objects
* object is a group together a set of variables and functions to create a modelling you would recognize in your real world.

* in an object variables called proprieties which tell us about the object .
* In an object functions become knows as Methods that represent tasks that are associated with the object.
* the proprieties and methods in an object have value and key .
* You can access the proprieties and methods in an object by using dot or square brackets . 

 var hotel = { <br>
name : 1 Quay 1 ,<br>
rooms=30,<br>
booked=15;<br>
roomTypes:['twin','double','suite'],<br>
**in the above this called proprieties** <br>

checkAvailability:function(){<br>return this.rooms-this.booked;<br>}

## Document Object Mode
* The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.



### WORKING WITH THE DOM TREE

Accessing and updating the DOM tree involves two steps:

1: Locate the node that represents the element you want to work with.

2: Use its text content, child elements, and attributes.

ACCESSING ELEMENTS

* DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.
