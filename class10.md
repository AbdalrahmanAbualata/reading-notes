# JavaScript 

## Error Handling & Debugging
* JavaScript can be hard to learn and everyone makes
mistakes when writing it. This chapter will help you learn
how to find the errors in your code. It will also teach you how
to write scripts that deal with potential errors gracefully.

### ORDER OF EXECUTION
* To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run:
### EXECUTION CONTEXTS
* The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope.
* Every statement in a script lives in one of three
execution contexts:
  * **GLOBAL CONTEXT**: Code that is in the script, but not in a function.
There is only one global context in any page.
  * **FUNCTION CONTEXT**: Code that is being run within a function.
Each function has its own function context.
  * **EVAL CONTEXT (NOT SHOWN)** : Text is executed like code in an internal function
called eva l {) .
### VARIABLE SCOPE
* **GLOBAL SCOPE**
If a variable is declared outside a function, it can
be used anywhere because it has global scope.
If you do not use the var keyword when creating
a variable, it is placed in global scope.
* **FUNCTION-LEVEL SCOPE**
When a variable is declared within a function,
it can only be used within that function. This is
because it has function-level scope.
### The stack 
* the js interpreter processe one line of code at a time when a statement needs data from another function ,it stacks the new function on the top of  current task.

### EXECUTION CONTEXT & HOISTING 
* Each time a script enters a new execution context, there are two phases
of activity:

1-. PREPARE
*  The new scope is created
* Variables, functions, and arguments are created
* The value of the this keyword is determined
2.  EXECUTE
* Now it can assign values to variables
* Reference functions and run their code
*  Execute statements

* Call functions before they have been declared
(if they were created using function declarations
- not function expressions)
• Assign a value to a va ria ble that has not yet been
declared
This is because any variables and functions within
each execution context are created before they are
executed.
The preparation phase is often described as taking
all of the variables and functions and hoisting them
to the top of the execution context. Or you can think
of them as having been prepared.
Each execution context also creates its own
variab1es object. This object contains details of all
of the variables, functions, and parameters for that
execution context.
### UNDERSTANDING SCOPE
* In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's variables object.
### UNDERSTANDING ERRORS
* If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handling code.
### ERROR OBJECTS
* Error objects can help you find where your mistakes are
and browsers have tools to help you read them.
### A DEBUGGING WORKFLOW
* WHERE IS THE PROBLEM?
    * First, should try to can narrow down the area where
the problem seems to be. In a long script, this is
especially important.
    * WHAT EXACTLY IS THE PROBLEM?
Once you think that you might know the rough area
in which your problem is located, you can then try to
find the actual line of code that is causing the error.
### HOW TO LOOK AT ERRORS IN CHROME
* The console will show you when there is an
error in your JavaScript. It also displays the line
where it became a problem for the interpreter.
### TYPING IN THE CONSOLE IN CHROME
* You can also just type code into the console
and it will show you a result.
### BREAKPOINTS
* You can pause the execution of a script on any
line using breakpoints. Then you can check the
va lues stored in variables at that point in time.