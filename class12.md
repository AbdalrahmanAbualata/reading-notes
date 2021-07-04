# Chart.js(Canvas)
A chart is a graphical representation for data visualization, in which “the data is represented by symbols, such as bars in a bar chart, lines in a line chart, or slices in a pie chart”. A chart can represent tabular numeric data, functions or some kinds of quality structure and provides different info.

## How do you create a chart in JavaScript?
* You can create responsive charts with JSCharting through a couple simple steps:

    * Download Chart.js

    * copy chart.min.js from the folder into the directory you'll be working with.

    * Create new html page.

    * Import the xcript. 

* Define a < div > tag in the HTML file with a unique id.
Provide this id, data, and any other options when calling JSC. Chart() in the JavaScript file.
Create the Context Using JavaScript
The first thing we need in the JavaScript is the context of our chart, which is basically just a fancy way of saying the element that we’re going to apply the chart to, which is our canvas object.

* So we’re going to create a variable called context, or ctx for short, and we’ll set this equal to that canvas object. And we’re going to point to that canvas object using jQuery. So I’m gonna use the dollar sign and parentheses, and inside the parentheses, we’ll have a set of quotation marks, and inside the quotation marks, we’ll use the CSS selector for that canvas object. And we’re pointing to that object’s ID, so we’re going to type # and then the ID, which is line-chart, and then add a semi-colon at the end of that statement.

* Add the JavaScript Code to Plot the Chart
Now that we’ve done that, we just need one more line of code to create our chart. Now it’s going to be a complex line of code, and it’s actually going to end up looking like multiple lines, but it’s just going to be one JavaScript statement.

## Basic usage of canvas
* This looks a lot like the  element, the only difference is that it doesn’t have the src and alt attributes. The 

* The id attribute isn’t specific to the Fallback content Because this is very straightforward: we just provide alternative content inside the canvas element. Browsers which don’t support .

* For example, we could provide a text description of the canvas content or provide a static image of the dynamically rendered content. This can look something like this:

* Required < /canvas > tag
In the Apple Safari implementation, If fallback content is not needed, a simple < canvas id=”foo” …>< /canvas > will be fully compatible with both Safari and Mozilla – Safari will simply ignore the end tag.

If fallback content is desired, some CSS tricks must be employed to mask the fallback content from Safari (which should render just the canvas), and also to mask the CSS tricks themselves from IE (which should render the fallback content).
## Drawing shapes with canvas
* Now that we have set up our canvas environment, we can get into the details of how to draw on the canvas. By the end of this article, you will have learned how to draw rectangles, triangles, lines, arcs and curves, providing familiarity with some of the basic shapes. Working with paths is essential when drawing objects onto the canvas and we will see how that can be done.

 ### The grid
* Before we can start drawing, we need to talk about the canvas grid or coordinate space Normally 1 unit in the grid corresponds to 1 pixel on the canvas. 
* The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y). Later in this tutorial we'll see how we can translate the origin to a different position, rotate the grid and even scale it, but for now we'll stick to the default .
### Applying styles and colors
* Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

* fillStyle = color Sets the style used when filling shapes. strokeStyle = color Sets the style for shapes' outlines. color is a string representing a CSS , a gradient object, or a pattern object. We'll look at gradient and pattern objects later. By default, the stroke and fill color are set to black (CSS color value #000000).