# HTML ,Object-Oriented Programming
## tables:

### what is table??

A table represents information in a grid format.<br>

How to create tables ??:<br>

* in order to create it we use : **< table>** [main element] , **< tr>** [start row] , **< td>** [table data], **< th>** [heading for column or a row].<br>


* For long tables you can split the table into a **< thead>**, <** tbody>**, and **< tfoot>**.

### functions:
* it is a block of code designed to perform a particular task.
it is executed when "something" invokes it (calls it).
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().
Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).
When JavaScript reaches a return statement, the function will stop executing.
### Methods :

* JavaScript methods are actions that can be performed on objects.
* Methods are stored in properties as function definitions.
A JavaScript method is a property containing a function definition.
You access an object method with the following syntax: objectName.methodName().




### Objects :

* You define (and create) a JavaScript object with an object literal.
The name:values pairs in JavaScript objects are called properties.
You can access object properties in two ways: objectName.propertyName or objectName[" propertyName"]
Objects can also have methods.

## Domain Modeling

### **Domain modeling** is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain.
### Model epic fails videos
* the two essential metrics for gauging popularity are:

         * An epic rating

         * whether or not the video has animals


* To define the same properties between many objects, you'll want to use a constructor function. Below is a table that summarizes a JavaScript representation of an EpicFailVideo object.
### Here's some tips to follow when building your own domain models.
* When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors. Model its attributes with a constructor function that defines and initializes properties. Model its behaviors with small methods that focus on doing one job well. Create instances using the new keyword followed by a call to a constructor function. Store the newly created object in a variable so you can access its properties and methods from outside. Use the this variable within methods so you can access the object's properties and methods from inside.

## OBJECTS
### WHAT ARE BUILT-IN OBJECTS?

* Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window. These built-in objects act like a toolkit for creating interactive web pages.

### THE DOCUMENT OBJECT

* The topmost object in the Document Object Model (or DOM) is the document object. Here are some properties of the document object, which tell you about the current page.

* PROPERTY	DESCRIPTION
    * document.title	Title of current document
    *  document. lastModified	Date on which document was last modified
     * document .URL	Returns string containing URL of current document
     * document.domain	Returns domain of current document
### DATA TYPES REVISITED
* Number
* Boolean
* String
* Null
* Undefined
* Object
### GLOBAL OBJECTS: MATH OBJECT
* PROPERTY	DESCRIPTION
    * Math.PI	Returns pi (approximately 3.14159265359)
METHOD	DESCRIPTION
    * Math.round()	Rounds number to the nearest integer
    * vMath.sqrt(n)	Returns square root of positive number, e.g., Math. sqrt (9) returns 3
    * Math.ceil()	Rounds number up to the nearest integer
WORKING WITH DATES & TIMES

* The order and syntax for this is:

       * Year four digits
       * Month 0-11 (Jan is 0)
       * Day 1-31
       * Hour 0-23
       * Minutes 0-59
       * Seconds 0-59
       * Milliseconds 0-999