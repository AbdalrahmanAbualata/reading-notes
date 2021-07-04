# Images
* IMAGES
Controlling the size and alignment of
your images using CSS keeps rules that
affect the presentation of your page in
the CSS and out of the HTML markup.
## CONTROLLING sizes OF IMAGES IN CSS 
* You can control the size of an
image using the width and
height properties in CSS, just
like you can for any other box.
Specifying image sizes helps
pages to load more smoothly
because the HTML and CSS
code will often load before the
images, and telling the browser
how much space to leave for an
image allows it to render the rest
of the page without waiting for
the image to download.
* You might think that your site
is likely to have images of all
different sizes, but a lot of sites
use the same sized image across
many of their pages.
* Whenever you use consistently
sized images across a site,
you can use CSS to control
the dimensions of the
images, instead of putting the
dimensions in the HTML.
## AligNing images Using CSS
* the float property can be used
to move an element to the left or
the right of its containing block,
allowing text to flow around it.
* Rather than using the **< img>**
element's align attribute, web
page authors are increasingly
using the float property to align
images. There are two ways that
this is commonly achieved:
1: The float property is added
to the class that was created to
represent the size of the image
(such as the small class in our
example).
2: New classes are created with
names such as align-left or
align-right to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.
## Centering images Using CSS
* By default, images are inline
elements. This means that they
flow within the surrounding text.
In order to center an image, it
should be turned into a blocklevel
element using the display
property with a value of block.
Once it has been made into a
block-level element, there are
two common ways in which you
can horizontally center an image:
1: On the containing element,
you can use the text-align
property with a value of center.
2: On the image itself, you can
use the use the margin property
and set the values of the left and
right margins to auto.
## Background Images
### background-image
* The background-image
property allows you to place
an image behind any HTML
element. This could be the entire
page or just part of the page. By
default, a background image will
repeat to fill the entire box.
The path to the image follows
the letters url, and it is put
inside parentheses and quotes.
## Repeating Images
### background-repeat
### background-attachment
* The background-repeat
property can have four values:
1. **repeat**
The background image is
repeated both horizontally and
vertically (the default way it
is shown if the backgroundrepeat
property isn't used).
* **repeat-x**
The image is repeated
horizontally only (as shown in
the first example on the left).
* **repeat-y**
The image is repeated vertically
only.
* **no-repeat**
The image is only shown once.
<hr>

* The background-attachment
property specifies whether a
background image should stay in
one position or move as the user
scrolls up and down the page. It
can have one of two values:
1. fixed
The background image stays in
the same position on the page.
2. scroll
The background image moves
up and down as the user scrolls
up and down the page
## Background Position
### background-position
* When an image is not being
repeated, you can use the
background-position
property to specify where in the
browser window the background
image should be placed.
This property usually has a pair
of values. The first represents
the horizontal position and the
second represents the vertical
**background-position: center top ;**
* If you only specify one value,
the second value will default to
center.
* You can also use a pair of pixels
or percentages. These represent
the distance from the top left
corner of the browser window
(or containing box). The top left
corner is equal to 0% 0%. The
example shown, with values of
50% 50%, centers the image
horizontally and vertically 
**background-position: 50% 50%;**
## CSS 3: Gradients
* CSS3 is going to introduce the
ability to specify a gradient for
the background of a box. The
gradient is created using the
background-image property
and, at the time of writing,
different browsers required a
different syntax.
Since it is not supported by all
browsers, it is possible to specify
a background image for the box
first (which would represent the
gradient) and then provide the
CSS alternatives for browsers
that support gradients 
**background-image: -o-linear-gradient(#336666,
#66cccc);**

# Practical Information
## Search Engine Optimization (SEO)
* Search engine optimization (or
SEO) is the practice of trying
to help your site appear nearer
the top of search engine results
when people look for the topics
that your website covers.

* At the heart of SEO is the idea of
working out which terms people
are likely to enter into a search
engine to find your site and then
using these terms in the right
places on your site to increase
the chances that search engines
will show a link to your site in
their results.
* In order to determine who comes
first in the search results, search
engines do not only look at what
appears on your site. They also
consider how many sites link
to you (and how relevant those
links are). For this reason, SEO
is often split into two areas:
on-page techniques and off-page
techniques.
### On-Page Techniques
On-page techniques are the
methods you can use on your
web pages to improve their
rating in search engines.
The main component of this is
looking at keywords that people
are likely to enter into a search
engine if they wanted to find
your site, and then including
these in the text and HTML code
for your site in order to help the
search engines know that your
site covers these topics.
Search engines rely very heavily
on the text that is in your pages
so it is important that the terms
people are going to search for
are in text. There are seven
essential places where you want
your keywords to appear.
Ensuring that any images have
appropriate text in the value of
their alt attribute also helps
search engines understand the
content of images.
### Off-Page Techniques
Getting other sites to link to you
is just as important as on-page
techniques. Search engines help
determine how to rank your
site by looking at the number of
other sites that link to yours.
They are particularly interested
in sites whose content is related
to yours. For example, if you
were running a website that
sold fish bait, then a link from
a hairdresser is not likely to be
considered as relevant as one
from an angling community.
Search engines also look at the
words between the opening
**< a >** tag and closing **< /a >** tag
in the link. If the text in the link
contains keywords (rather than
just click here or your website
address) it may be considered
more relevant.
The words that appear in links to
your site should also appear in
the text of the page that the site
links to.
## On-Page SEO
* **In every page of your website there are seven key places where keywords
(the words people might search on to find your site) can appear in order
to improve its findability**.
1.  Page Title. 
2. URL / Web Address.
3. Headings.
4. Text.
5. Link Text.
6. Image Alt Text.
7. Page Descriptions.
## How to Identify Keywords and Phrases
* Determining which keywords to use on your site can be one of the
hardest tasks when you start to think about SEO. Here are six steps that
will help you identify the right keywords and phrases for your site.
1. **Brainstorm**:List down the words that
someone might type into
Google to find your site. Be sure
to include the various topics,
products or services your site is
about.
2.  **Organize**: 
Group the keywords into
separate lists for the different
sections or categories of your
website.
3. **Research**:There are several tools that let
you enter your keywords and
then they will suggest additional
keywords you might like to
consider, such as:
adwords.google.co.uk/
select/KeywordToolExternal
(When using this tool, select the
"exact match" option rather than
"broad match.")
www.wordtracker.com
www.keyworddiscovery.com
4. **Compare**:It is very unlikely that your
site will appear at the top of
the search results for every
keyword. This is especially true
for topics where there is a lot
of competition. The more sites
out there that have already been
optimized for a given keyword,
the harder it will be for you to
rise up the search results when
people search on that term.
5.  **Refine**: 
Now you need to pick which
keywords you will focus on.
These should always be the ones
that are most relevant to each
section of your site.
6.  **Map**
Now that you have a refined list
of keywords, you know which
have the most competition, and
which ones are most relevant,
it is time to start picking which
keywords you will use for each
page.
