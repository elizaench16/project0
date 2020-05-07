# Project 0

Web Programming with Python and JavaScript

As my project, I decided to have some fun and created an "Alumni Website" for Hogwarts.

There are 5 HTML files - one for each Hogwarts House as well as one for Hogwarts in general (the Great Hall page).

There is also a stylesheet written using SCSS.

The other requirements of Project 0 were fulfilled as follows:


SASS variables:
  The House colors are all stored in variables at the top of the stylesheet. As I altered colors and color implementation frequently, this allowed me to quickly change the colors without having to go deep in the code or change it in multiple places. I also used a variable to set the border width.

.class creation and Inheritance:
  As each house has identical formatting with house-specific colors, I created a .house class and used @extend to create a class for each house, in which I specified the colors.

Nesting:
  The formatting regarding the styling of divs  that are inside of containers.

Hyperlinks for site navigation:
  I included a navbar from bootstrap that allows for site navigation through hyperlinks to each of the pages.

@media queries for responsive coding:
  I included a "pageguide" div on each page. This only appears when the screen size is below 992 pixels (an average laptop size), and allows for easier page navigation to reduce scrolling.

#id selector:
  I used the #id selector to label each of the three content divs on each page, and used those #ids in local links in the "pageguide" div in each page to jump to the selected div to reduce scrolling when in a smaller screen size.

Bootstrap component:
  The navbar is a Bootstrap component. It is also responsive, altering to a vertical configuration when screen size is small.

Bootstrap grid:
  Each div is formatted using the Bootstrap grid format.

Tables, images, and lists:
  Each house page includes a table. The Slytherin and Gryffindor pages include ordered lists, the Great Hall and Slytherin pages include unordered lists. All pages include at least two images - the house crest as well as the Hogwarts crest in the navbar.

CSS selectors and properties:
  CSS selectors used include div, img, h1, h3, h4, ul, ol, input, etc.
  CSS properties used include font-family, font-style, color, background-color, font-weight, etc.



Other sources used include the Bootstrap page, W3, and stackexchange.
