# React and Forms
### What is a ‘Controlled Component’?
* It’s one that takes its current value through props and notifies changes through callbacks like onChange. A parent component “controls” it by handling the callback and managing its own state and passing the new values as props to the controlled component.

 

### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
* Update the state with their responses as soon as they enter them, because that allows us to keep the data for the user if they close the page by mistake or something similar.

 

### How do we target what the user is entering if we have an event handler on an input field?
* by calling a function each time this changes.


 ## Why would we use a ternary operator?
if we want a quick way to choose between two options.

 

## Rewrite the following statement using a ternary statement:
*       if(x===y){
          console.log(true);
             } else {
           console.log(false);
              }
* you do that through:

          let o = x===y ? true : false;
          console.log(o);