# Passing Functions as Props
## React Docs - lists and keys
### What does .map() return?
* New array.
### If I want to loop through an array and display each value in JSX, how do I do that in React?
* Using .map(), we let  every value in the array we are mapping go through html-like code we want it in.
### Each list item needs a unique ____.
* Key.

 ### What is the purpose of a key?
 * Keys help React identify which items have changed, are added, or are removed.

 ## The Spread Operator
 ### What is the spread operator?
 * it spread syntax “spreads” the array into separate arguments.

### List 4 things that the spread operator can do.
*     Copying an array
      Concatenating or combining arrays
      Using Math functions
      Using an array as arguments
 
 ### Give an example of using the spread operator to combine two arrays0.
*          const hello = ['hello']
           const world = ['world']
          const helloWorld = [...hello,...world]
          console.log(...helloWorld) // hello world
### Give an example of using the spread operator to add a new item to an array.
*          const fruit1  = ['apple', 'pineapple', 'banana']
           const fruit2 = ['orange']

           const fruits = [...fruit1,...fruit2]
           console.log(...fruits) // apple pineapple banana orange


### Give an example of using the spread operator to combine two objects into one.
*           const hello = {hello: “hayoo”} const world = {world: “globe”}

            const helloWorld = {…hello,…world} console.log(helloWorld) // Object { hello: “hayoo”, world: “globe” }

## How to Pass Functions Between Components
### In the video, what is the first step that the developer does to pass functions between components?
*  by making a constructor and using the object state .

### In your own words, what does the increment function do?
* Increase the number besides the names the instructor used.

 
 ### How can you pass a method from a parent component into a child component?
 * By passing it as an attribute through the parent to the child (example: increment={this.increment}).

 ### How does the child component invoke a method that was passed to it from a parent component?
 * You can call it through the **this.props.increment()**.

