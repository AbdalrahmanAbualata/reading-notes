# FUNCTIONAL PROGRAMMING
## Reading
### What is functional programming?
* a style of building the structure and elements of computer programs, that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

 

### What is a pure function and how do we know if something is a pure function?
* It returns the same result if given the same arguments, and It does not cause any observable side effects.

 

### What are the benefits of a pure function?
* You’ll always get the same result, as all the code a pure function uses is inside of it or gets past to it as parameters.

 

### What is immutability?
* When talking about data, it means the state of the data cannot be changed after it’s created.

 

### What is Referential transparency?
* if a function consistently yields the same result for the same input, it is referentially transparent.

 

## Videos
### What is a module?
* Modules are small-ish certain packages of code and js files that we can use to do specific things, we use them so we don’t have to download a metric ton of code everytime, and instead just get this comparatively small number of files.

 

### What does the word ‘require’ do?
* require imports and gets the module from the specified path, so you can not use the module in any file you want.

 

### How do we bring another module into the file the we are working in?
* *y assigning a variable to whatever require gets from the the modules.

 

### What do we have to do to make a module available?
* you first have to export it, using module.export = function;