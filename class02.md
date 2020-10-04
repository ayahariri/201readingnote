# Detailed Basics of HTML, CSS and Javascript

## HTML Basics (more information)

As previously mentioned we have to break down the lnaguage in order for us to write our html. Kindly find the table below for most html basics:

HTML Tag | Referrence
---------|------------
< h1 > to < h6 > | headings and their sizes
< p > | text/paragraph
< b > | to make text bold
< i > | to make text italic
< sup > | characters to be superscripted (smaller and up)
< sub > | characters to be subscripted (smaller and down)
< br > | to create a line break/white space
< hr > | to create an actual line break with a line
< strong > | to indicate the text's importance.
< q > | used for quotes
< blockquote > | used for long quotes
< abbr title="x" > X</abbr> | for abbreviations
< acronym title="x"> X</acronym > | to spell out the full form of the acronym  
< cite > | referencing a book, film, research paper, article, etc

## CSS Basics (more information)

It is essential to try and imagine all content of CSS as boxes. Then CSS associates style rules with html elements by selectors and declaractions.

So for : p {
    font-family: Arial;}
The *p* is the **selector** and the *(font-family: Arabia;)* is the **declaration**.

**Selectors** indicate which element the rule applies to, while **Declarations** indicate how the element of *selector* should be *styled*.

CSS properties affect how elements are displayed.

### Ways to use CSS

There are 3 ways in which one can use CSS.

#### A. External use of CSS

The *external* use is simply adding a link to your html that connects and activates the CSS codes, such as; < link href="css/styles.css" >.
One can also add the following to specify the type of document and relationshion;
< link href="css/styles.css" > type="text/css" rel="stylesheet" />

#### B. Internal use of CSS

The *internal* use is simply adding a style tag < style > in the body, preferably at the bottom, and closing the tag.

#### C. Inline use of CSS

The *inline* refers to adding the css style inside an html tag. For example: 
< p style = "color:green;">

### CSS Selectors

CSS *selectors* allow you to target rules to specific elements in an HTML document.
The table below shows the types of CSS selectors:

Selector | Example | Meaning
**Universal Selector** | * {} | Applies to all elements in the document
**Type Selector** | h1, h2, {} | matches element name, here is heading
**Class Selector** | .note{} OR p.note {} | matches class, which is is note OR matches only paragraph with that class
**ID Selector** | #intro {} | matches elements who's id is called intro

## JavaScript Basics (more information)

Just like the CSS, JavaScript also has several use it can be implemented.
Either by adding a script tag < script > </ script > or by writting them in a seperate file, which is usually prefered. To be done on a seperate file, a link should be on the html, which goes as follow: (should be inside body depending on where you want the loading to stop)

< script src="js/add-content.js" ></script>

JavaScript is basically split into objects and methods. Here is an example:

- document.write('Good morning!');

In this casa, **document** is the *object* that represents the entire web page. **write()** is the *method* of the document object that allow new content to be written on the page of the < script >.

**Variables** are very important to make the script store its data.

### Additional Information for JS (not basic)

Comments are used to explain the code below or add a comment by simply using /*
