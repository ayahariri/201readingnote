# Links on HTML

Links allow you to move from one web page to another — enabling the very of browsing. Links are done by:

< a href="http://www.imdb.com" >IMDB< /a >

There are several ways to use links on HTML:

- **Linking to other sites** by < a href="url" >
- **Linking to other pages on the same site** by adding the url to the page inside the href
- **Linking to a specific part of the same page**
by < a href="#arc_shot">Arc Shot< /a > < br />

## Relative URLS

Relative URLS help you link to other pages on the same site. Here are areas that we can link to:

Relative Link Type | Example
-------------------|--------
Same Folder | < a href="reviews.html">Reviews</a>
Child Folder | < a href="music/listings.html">Listings</a>
Grandchild Folder |< a href="movies/dvd/reviews.html">
Parent Folder | < a href="../index.html">Home</a>
Grandparent Folder | < a href="../../index.html">Home</a>

## The Directory Structure

When websites are large, it is preferable to organize your code by placing the pages of different sections into a new folder (structure - relationships - homepages)

## Layout

### Positioning elements

CSS treats each HTML element as if it is in its own box, by being either or block leverl box or an inline box (h1, p, ul, li)

**Block level element** : start on a new line
**Inline elements** : FLow in between surrounding text
(img, b, i)

### Controlling the position of an element

CSS has different positioning schemes that allow you to control tge layout of the page:

1. Normal flow (every block-level element appears on a new line)
2. Relative positioning (moves an element from the position it would normally be)
3. Absolute positioning (positions an element in relation to its containing element)

To indicate where a box should be positioned we need the box offset properties;

- Fixed positioning: positions the element in relation to the brower window
- Floating element: allows you to take that element out of normal flow and position it to the far left or right of a containing box

### Postition CSS syntax

Property | syntax
--------------|----------
Normal Flow | position:static
Relative Position  | position:relative
Absolute Postion | postion:absolute
Fixed Postion | position:fixed

## JavaScript Scripts

 A **script** is made up of a series of statements. Each statement is like a step in a recipe. They contain very precise instructions; like specifying that a value has to be stroed before creating a calculation.

**Variables** on the other hand are used to temporarily store the information for it to run. To make it more organised, *arrays* are used to store more than one piece of the related information.

JavaScript can recognize the following:

- Numbers (0-9)
- Strings ('text')
- Boolean (true or false)

Then come the *expressions* which evaluate into a single value and rely on *operators* to calculate the value.

The browser requires very detailed instructions in order to render and run your code. They can get very long and messy. A way to organize them is by using the following:

- Functions & Methods
    • functions let you group a series of statements together to perform  specifc task.
        - To declare a function:
        function sayHello() {
            document.write('Hello!');
        }
    Functiones need to be called and declared.
- Objects
- Built-in objects

## 6 Reasons for Pair Programming

Pair programming usually involves two roles:

1. *The Driver* is the programmer who is typing and the only one whose hands are on the keyboard.
2. *The Navigator* thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs.

Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.

### Why is it beneficial

- Greater Efficiency
- Engaged Collaboration
- Learning from others
- Developping Social Skills
- Ready for Job Interview
- Comfortable around work environement
