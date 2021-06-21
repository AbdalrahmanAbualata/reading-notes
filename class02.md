## Text in **HTML**
### Headings
* there is six level of heading in **HTLM** from h1 to h6 .
* **h1** is used for main headings , **h2** is used for subheadings
If there are further sections
under the subheadings then the
**h3** element is used, and so
on...

* Browsers display the contents of
headings at different sizes , starting from **h1** is the biggest one then going to be smaller until **h6** .
### Paragraphs 
* To create a paragraph, surround
the words that make up the
paragraph with an opening **< p >**
tag and closing **</ p >** tag.
* By default, a browser will show
each paragraph on a new line
with some space between it and
any subsequent paragraphs.
### **Bold** & ***Italic***
* The worlds between this tags  **< b >** and **</ b >** can make characters appear **bold**.
* The worlds between this tags  **< i >** and **</ i >** can make characters appear ***Italic***.
### Superscript & Subscript
* The **< sup >** element is used
to contain characters that
should be superscript such
as the suffixes of dates or
mathematical concepts like
raising a number to a power. 
* The **< sub >** element is used to
contain characters that should
be subscript. It is commonly
used with foot notes or chemical
formulas .
### Line Breaks & Horizontal Rules
* **There are a few elements that
do not have any words between
an opening and closing tag. They
are known as empty elements like ***(< br/ > and < hr / >)***
and they are written differently.**

* if you wanted <br/>
to add a line break <br/> inside the
middle of a paragraph you can
use the line break tag **< br / >**.
* To create a break between
themes — such as a change of
topic in a book or a new scene
in a play — you can add a
horizontal rule between sections
using the **< hr />** tag.<hr/>
   <hr/>

## Introducing CSS
### Understanding CSS: Thinking Inside the Box
* The key to understanding how CSS works is to
imagine that there is an invisible box around
every HTML element.
#### BLOCK & INLINE ELEMENTS
* **Block** level elements look
like they start on a new line.
Examples include the < h1 >-
< h6 >, < p > and < div > elements.
* **Inline** elements flow within the
text and do not start on a new
line. Examples include < b >, < i >,
< img >, < em > and < span >.

### CSS Associates Style rules with HTML elements
* CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.
* **Selectors :**
      indicate which
element the rule applies to.
The same rule can apply to
more than one element if you
separate the element names
with commas.
* **Declarations:** 
indicate how
the elements referred to in
the selector should be styled.
Declarations are split into two
parts (a property and a value),
and are separated by a colon.
### CSS Properties Affect How Elements Are Displayed
* CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon.
* **Properties** indicate the aspects
of the element you want to
change. For example, color, font,
width, height and border.
* **Values** specify the settings
you want to use for the chosen
properties. For example, if you
want to specify a color property
then the value is the color you
want the text in these elements
to be.

