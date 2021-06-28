## Layout
### Building Blocks
* CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.
* **Block-level boxes** start on a new line and act as the main building blocks
of any layout **(< h1 > < p > < ul > < li >)**.

* **inline boxes** flow between surrounding text **(< img > < b > < i >).
### Containing Elements
* If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element like **(< div > < section> )**.
* A box may be nested inside
several other block-level
elements. The containing
element is always the direct
parent of that element.
### Controlling the Position of Elements 
* CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.
### Normal Flow
* position : static ; n normal flow, each block-level
element sits on top of the next
one. Since this is the default
way in which browsers treat
HTML elements, you do not
need a CSS property to indicate
that elements should appear
in normal flow, but the syntax
would be:
**position: static;**
### Relative Positioning
* **position : relative** :Relative positioning moves an
element in relation to where it
would have been in normal flow.
For example, you can move it 10
pixels lower than it would have
been in normal flow or 20% to
the right.
### Absolute Positioning
* **position:absolute** :When the position property
is given a value of absolute,
the box is taken out of normal
flow and no longer affects the
position of other elements on
the page. (They act like it is not
there.)
The box offset properties (top
or bottom and left or right)
specify where the element
should appear in relation to its
containing element.
