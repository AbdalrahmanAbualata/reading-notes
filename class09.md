# Forms

* example (the search box).

## There are several types of form controls that you can use to collect information from users:

1- ADDING TEXT.

2-Making Choices.

3-Submitting Forms.

## How does an HTML Form work?
* Your visitor loads the form page in her web browser. The browser sends a request to the web server.
* Your visitor fills the form and submits it. .
* The form submission data is sent to the web server.
* The web server processes the request.
* A response is sent back to the browser.
* Password Input

* < input > type=”password” When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out. They are hidden in this way so that if someone is looking over the user’s shoulder, they cannot see sensitive data such as passwords.

* name The name attribute indicates the name of the password input, which is sent to the server with the password the user enters.

* size, maxlength It can also carry the size and maxlength attributes like the the single-line text input.

* Lists, Tables and Forms
Specifying bullet point styles
Adding borders and backgrounds to tables
Changing the appearance of form elements There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms.

* In this chapter you will learn how to:

* Specify the type of bullet point or numbering on lists

* Add borders and backgrounds to table cells
Control the appearance of form controls
Together, these properties allow you to take finer control over specific parts of your pages.
# EVENT 
* Scripts  respond to  events by updating the content of the web page (via the
Document Object Model) which makes the page feel more interactive.
 ### INTERACTIONS EVENTS
 * Events occur when users click or tap on a link, hover or swipe over an element,type on the keyboard,resize the window, or when the page they requested has loaded.
 ### EVENTS TRIGGER CODE
 * When an event occurs, or fires, it can be used to trigger a particular function. Different code can be triggered when users interact with different parts of the page. 
 ### CODE RESPONDS TO USERS
 * The events can trigger the-kinds of changes the DOM
 is capable of. This is how a web page reacts to users.

 ## HOW EVENTS TRIGGER JAVASCRIPT CODE
 * **When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.
Together these steps are known as event handling.**
1. Select t he element
node(s) you want the
script to respond to.
For example, if you want to
trigger a function when a user
clicks on a specific link, you need
to get the DOM node for that
link element. You do this using a
DOM query . 
2. Indicate which event on
the selected node(s) will
trigger the response.
Programmers call this binding an
event to a DOM node.
3. State the code you want
to run when the event
occurs.
When the event occurs, on a
specified element, it will trigger
a function. This may be a named
or an anonymous function.

* **The UI events that relate to the
browser window (rather than the
HTML page loaded in it) work
with the window object rather
than an element node.**
* Some events work with most
element nodes, such as the
mouseover event, which is
triggered when the user rolls
over any element. Other events
only work with specific element
nodes, such as the submit event,
which only works with a form.
3
State the code you want
to run when the event
occurs.
When the event occurs, on a
specified element, it will trigger
a function. This may be a named
or an anonymous function.

## THREE WAYS TO BIND AN EVENT TO AN ELEMENT
* Event handlers let you indicate which event you
are waiting for on any particular element. <br>
There are three types of event handlers.
1. HTML EVENT
HANDLERS
2. TRADITIONAL DOM
EVENT HANDLERS
3. DOM LEVEL 2 EVENT
LISTENERS
### EVENT LISTENERS 
* Event listeners are a more recent approach to handling events.
They can deal with more than one function at a time
but they are not supported in older browsers.<br>
* Here is the syntax to bind an event to an element using an event listener,
and to indicate which function should execute when that event fires:<br>
**element .addEventlistener('event', functionName [, Boolean]) ;**
