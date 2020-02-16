# HTML Reading Summary
------------------------

# Introduction

## Creating web pages:
Web pages are created mainly using HTML and CSS.

- HTML
    - HTML is the *foundation* of web pages.
    - HTML is used to create the building structure of web pages and to add the content of the pages by writing words.
    - tags and elements are added to the words so that the browser can interpret the content.
    - currently, the latest version of HTML is HTML5 which introduces new tags.
- CSS
    - CSS provides the *design* for web pages.
    - you control the styling and layout of web pages with CSS using rules.
    - CSS properties, which are used in your CSS rules, are categorized into:
        1. Presentation
        \> To control *how* things in your webpage (text, images, etc) are presented and how they appear  – To control the style of the content of your webpage.
        2. Layout
        \> To control *where* things in your webpage appear in the screen – To control the positions of the elements on the screen and use this to make your webpage more attractive.

## Accessing web pages:
The web is accessed by:

1. Web Browsers

    \> these are softwares used to access the web and websites
    \> web pages can be viewed using a browser by:
    - typing the web address of the web page into the browser.
    - following a link from another site.
    - using a bookmark

    \> new versions of browsers are regularly released, so web page visitors can only use the functionalities offered by their browsers according to their versions

2. Web Servers
    \> web servers are special computers that host websites and are optimized to send web pages when they are requested
    \> requests for web pages are sent from the web browser to the web server
    \> web servers send the web pages to the browsers as HTML and CSS code, browsers then interpret the HTML and CSS code to create the web page 
    \> in order for your browser to find the web server hosting the website you requested, it will first connect to what's called a * Domain Name System (DNS) server*
3. Devices

4. Screen Readers  



# HTML - Structure
----------------------
**\* The structure of a web page is described by HTML and is very important in helping readers to understand the messages you are trying to convey and to navigate around the web page.**  
i.e. headings and subheadings are used to reflect a hierarchy of information

- HTML is an acronym for HyperText Markup Language
    - the HyperText part refers to the fact that HTML allows you to create links for navigation
    -  a markup language allows you to annotate text (using code), and these annotations provide additional meaning to the content
- HTML describes the structure of a web page, by adding a code to the words we want to appear on the web page
- the HTML code is made up of **_elements_**, which are characters between  angled brackets
- HTML elements are made up of two **_tags_**, an openning tag and a closing tag with an extra ( \ ) in it, with the content between openning and the closing tags  
The characters in the tag brackets indicate the tag's purpose
- HTML elements tell the browser what is the type of the information that's between it's openning and closing tags
- The terms "tag" and "element" are often used interchangeably
- HTML attributes are used in the openning tag of an element, and are made up of two parts:
    1. a name
    2. a value

which are separated by an equals sign, such as:
=> attribute name = "attribute value"

- The attribute name  should be written in lowercase, and it indicates the extra information about the element content
- The attribute value should be placed in double quotes, and it  is the information or setting for the attribute

    - NOTE: 
HTML5 allows you to use uppercase attribute names and omit the quotemarks, but this is not recommended.
- The majority of attributes can only be used on certain elements
-  Most attribute values are pre-defined 

## Basic HTML elements:

- <head>
This element contains information about the page, that are not shown in the browser.  
A <title> element is usually inside the <head> element. 

- <body>  
Everything inside this element is shown inside the main browser window, so all the content is included inside this element

- <title>
This element contains the title that shows up in the browser title bar

# HTML - Extra Markup
---------------------------
## HTML versions:  
**Each new version of HTML has new elements and attributes added and older code removed**

1. HTML 4 — released 1997

2. XHTML 1.0 — released 2000

3. HTML5 — released 2000
    - do not need to close all tags
    - new elements and attributes are introduced

- Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using and to help it render the page correctly
    - this declaration  should be the first thing in a document. There must be nothing before it, not even a space.

## Comments in HTML:
**Use comments to make your code easier to read, and to indicate where sections of the page start or end, and to pass on notes to help anyone who is looking at the code understand it**  

**Another use of comments is to comment around blocks of code to stop that code from being displayed in the browser**

- for a single-line comment:  
add text/code inside this tag  `<!-- -->`

- for a multi-line comment:  
add text/code between a  ` \* ` and a ` *\ ` 

## ID Attribute: 
**An id attribute is used to uniquely identify an element from other elements on the page, and it can be carried every HTML element**

- id attributes are used in the openning tag of an element, as:  
` id = "value" `
- the value of the id attribute should start with a letter or an underscore 
- since an id attribute is unique to an element, no two elements on the same page should have the same value for their id attributes 
-  giving an element a unique identity allows you to style it (using CSS) differently than any other instance of the same element on the page
- using JavaScript, id attributes can be used to allow the script to work with that particular element
- The id attribute is known as a global attribute because it can be used on any element

## Class Attributes:
**Rather than uniquely identifying one element within a document, class attributes identify several elements as being different from the other elements on the page**

- the class attribute on any element can share the same value 

## Block Elements:
**Block elements always start on a new line in the browser window**

- examples of block elements are :
        <h1>, <p>, <ul>, and <li>

## Inline Elements:
**Inline elements always continue on the same line as their neighbouring elements**

- examples of inline elements are:
         <a>, <b>, <em>, and <img>

## Grouping text and Elements in a Block:
**A set of elements can be grouped together in one block-level box using the <div> element**

- you can use an id or class attribute on the <div> element so you can create CSS style rules to indicate how much space the <div> element should occupy on the screen and change the appearance of all the elements contained within it
- you can use a <div> element for each section of your page to make your code more organized and easier to follow

## Grouping text and Elements Inline:
**A set of elements can be grouped together inline  using the <span> element**
- <span> element is used to
    - contain a section of text to differentiate it from its surrounding text
    - contain a number of inline elements
- classes and id's can be used with <span> elements to explain their purpose and to apply CSS styles to them

## Iframes:
**An iframe, which is an abbreviation of inline frame, is a little window that has been cut into your page, in which you can see another page** 

- the content of the iframe can be any HTML page (located anywhere on the web) 
- attributes that can be used with an <iframe> element:
     - ` src` 
        specifies the URL of the page to show in the frame
    - ` height `
        specifies the height of the iframe in pixels
    - `width `
     specifies the width of the iframe in pixels
 

# HTML5 Layout

**New elements werer created in HTML5 to be used to help describe the structure of the page**
HTML5 new elements include:

1. <header>
1. <nav>
1. <article>
1. <aside>
1. <footer>

- <header> and <footer> elements can be used both for the main header and footer that appears on every page, or as a header and footer for an individual <article> or <section> within the page

- The <nav> element is used to contain the major navigational blocks on the site such as the primary site navigation, and it can also be used  for the links that appear at the bottom of every page 

- The <article> element acts as a container for any section of the page, and several <article> can be nested inside each other

- The purpode of the <aside> element depends on its position;
    - inside an <article> element: 
      it should contain information that is related to the article but not essential to its overall meaning
    - outside an <article> element:
       it acts as a container for content that is related to the entire page

- The <section> element groups related content together

- You can group together a set of one or more <h1> through <h6> elements so that they are treated as one single heading, using <hgroup> element

- To contain any content that is referenced from the main flow of an article, you can use the <figure> element

# Proccess and Design

## Tips for building and designing a website:

* When building a website, it's very important to consider the target audience
and design the website according to the information you have about them.

* Organize the information you want to present into sections or pages.

* Use a "site map" to help design your website.
site maps are diagrams of the pages that will be used to structure the site.

* Another useful technique is "card sorting", which is used to
help you decide what information should go on each page.

## Wireframes:
* A wireframe is a simple sketch of the key information that needs to go on each page of a site

* Wireframe involves sketching or shading areas where each element of the page will go 

* By creating a wireframe you can ensure that all of the information that needs to be on a page is included.


* The wireframes make design easier because you know what information needs to appear on which page

## Design to communicate:
* Organizing and prioritizing information on a page helps users understand its importance and what order to read it in

* Content design includes:
    - A masthead or logo 
    - Links to navigate the site
    - Links to related content
    - Login or membership options
    - Copyright information
 
* Grouping together related content into blocks or chunks makes the page look simpler, by presenting certain types of information in a similar visual style 

-----------------------------------

# JS Reading Summary
------------------------

# Introduction
---------------
## Javascript is used to make web pages more interactive by providing the following features:
1. Access Content
  - you can select any element, attribute or text from an HTML page

2. Modify Content
  - you can add or remove elements, attributes and text
  
3. Program Rules
  - you can give the browser accsess or let it change the content by giving it a set of specified steps
  
4. React to events
  - you can let the browser run a specific script after an event has occured, i.e., a button press or a link click
--------
**JS is powerful because it gives the ability to change an HTML page content while it's stil loading in the browser** 
and this is done by relying on the ability to: 
*Accsess
*Modify
*Program 
*React 
### Examples of using this ability in browsers are:
1. Slideshows
2. Forms
3. Reload part of the page
4. Filtering data
-----
# The ABC of Programming
---------------------------

## A: Scripts
**A script is a series of instructions that a computer can follow to achieve a goal**
- a computer follow these instructions step-by-step
- a browser uses different part of the script depending on how the user interacts with the webpage
- a script run different sectoions of the code depending on the situation

**To write a script:**
1. state your goal
2. list the tasks you need to complete the task
3. Design the script
4. Code each step
--------
# Expressions
---------------
**An expressions result in a single value** 
## Types of expressions:
1. Expressions that assign a value to a variable; using the assignment (=)
2. expressions that tow or more values to return a single value; using *operators*
## Arithmetic Operators:
are operators which you can use with numbers.

--------|---|----------------------------------
addition| + |adds one value to another
---------|---| ---------------------------------
subtraction| - |subtracts one value from another
-----------|---|---------------------------------
division| / |divides two values 
--------|---|------------------------------------
multiplication| * |multiplies two values
--------------|---|------------------------------
increment| ++ |adds one to the current number 
---------|---|-----------------------------------
decrement| -- |subtracts one from the current value
---------|---|-------------------------------------
modulus| % |divids two values and returns the reminder
-------|---|-----------------------------------------


## The String Operator:
the string operator is (+) and it's used to add two strings and join them

------
# Functions
---------------
**Functions are used to perform a specific task withuot repeating yourself (the DRY principle) by grouping a series of statements together**
- some functions need *parameters* which are values used to achieve the task
- the answer or response provided by the function is called a *return value*
- a function must be given a *function name*, when you want the function to perform the task you *call* it using the function name

## Declaring a Function:
functions are declared as follows:
**function-keyword function-name(parameters) {**
    **statement;**
   **}**
## Calling a Function:
functions are called as follows:
**function-name(parameters);**
