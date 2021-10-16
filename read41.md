
# Java Basics
_________________________________________

## Java is a programming language. ###

### Java is used to develop mobile apps, web apps, desktop apps, games and much more. ###

- Object − Objects have states and behaviors. Example: A dog has states - color, name, breed as well as behavior such as wagging their tail, barking, eating. An object is an instance of a class.

- Class − A class can be defined as a template/blueprint that describes the behavior/state that the object of its type supports.

- Methods − A method is basically a behavior. A class can contain many methods. It is in methods where the logics are written, data is manipulated and all the actions are executed.

### Variables:

- Instance Variables − Each object has its unique set of instance variables. An object's state is created by the values assigned to these instance variables.

- Class Variables (Static Fields) − the values of this varibles it will not change ever ,its one value for each varible .


   ## Operators
   In mathematics and sometimes in computer programming, an operator is a character that represents an action, as for example x is an arithmetic operator that represents multiplication and + represents addition . In computer programs, one of the most familiar sets of operators, the Boolean operators, is used to work with true/false values. Boolean operators include AND, OR, NOt
   [read more ](https://whatis.techtarget.com/definition/operator).
________________________________________________

## Expressions, Statements, and Blocks

## Expressions

are lines of code that contain variables and operators, work together to bring out a result, for example:

1 + 2

this is an expression that uses the operator "+" to generate a new value.

## Statements

 are a complete line of code than when we run it, we can have a final result and we alwa send it with a semicolon ";"

int result = 1 + 2;
## Blocks

 is a group of more than one statements between balanced braces.
 example:-

 class main {
public static void main(String[] args) {
int num = 10;
if (num >10 ) { // begin block 1
System.out.println("hello");
} // end block one
else { // begin block 2
System.out.println("bye");
} // end block 2
}
}

## compile code
- the computer can't understand any languge just can understand the 0,1 languge so we need to  convert the source code into a language that the computer understands (0,1 ).

* in case of java language the code not converting to the machine language directly but it converting to another language its bytecode . bytecode is readable by JVM(Java Virtual Machine) .

### Compiling a Java program is very easy after JDK installation. Following are the steps 

- Open a command prompt window and go to the directory where you saved the java program. Assume it's C:\.

- Type 'javac MyFirstJavaProgram.java' and press enter to compile your code. If there are no errors in your code, the command prompt will take you to the next line (Assumption: The path variable is set).
__________________________________________________________________

