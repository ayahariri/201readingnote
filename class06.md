# Javascript Functions & HTML DOM Tree

## JavaScript & their functions

When calling a function that has parameters, we specify the values it should use in the parentheses that follow the name. Values in functions are called *arguments* and they can be provided as values or variables.

**Arguments as values** getArea(3, 5);
**Arguments as variables** wallWidth = 3 ; wallHeight = 5; getArea(wallWidth, wallHeight);

When a calcualtion has been done, usually you find a return; So it would go like:
function calculatedArea(width, height){
    var area = width * height;
    return area;
}
var wallOne = calculatedArea (3, 5);
var wallTwo = calculatedArea (8, 5);
}

You can also get *multiple* values out of a function by:
function getSize(width, height, depth){
    var area = width * height;

    vat volume = width * height * depth;
    var sizes = [area, volume];
    return sizes;
}
var areaOne = getSize (3,2,3) [0] ;

var volumeOne = getSize ( 3,2,3 ) [1] ;

## What is a Dom Tree

The Dom Tree is a model of a web page, that is stored in the browser's memory. It consists of 4 main types of *nodes*.

1. The Document Node
2. The Element Nodes
3. The Attribute Nodes
4. The Text Nodes

![Dom Tree Graph](https://www.researchgate.net/profile/Jian_Chang4/publication/254002847/figure/fig1/AS:298235726974978@1448116346303/Example-of-DOM-Node-Tree.png)

Accessing and updating the DOM tree involves two steps:

1. Locate the node that represents the element you want to work with. 2. Use its text content, child elements, and attributes.

Selecting an element from a nodelist have two ways, the *item method* and the *array syntax.*

**The item method** will return an individual  node from the Nodelist. Where the elemt, the length property and storing the first element come in hand. Example:

var elements = document.getElementsByClassName('hot') ;if (elements.length>= 1) {
var firstltem = elements.item(O); }

**The array syntax** is preferred over the item method because is it faster. Before selecting a node from the Nodelist, check that it does contain nodes. You will need to create a Nodelist, then if statements, then get the first element from the Nodelist. Example:

var elements = document.getElementsByClassName('hot') ;if (elements.length>= 1) {
var firstltem = elements.item(O); }

There are different things to select elements for the Nodes, such as:

- selecting elements using class attributes
- selecting elements by tag names
- selecting elements using CSS selectors

### Adding or Removing HTML content

There are two different ways to adding or removing content on HTML:

1. from a DOM tree: the innerHTML propoerty, or
2. the DOM manipulation.

#### Adding elements and removing using Dom Manipulation

Dom manipulation offers another technique to add new content on a page:

1. *Create the element*
createElement()
2. *Give it content*
createTextNode()
3. Add it to the DOM
appendChild()

Dom manipulation can also be used to remove elements from the DOM tree:

1. *Store the element to be removed in a variable
2. Store the parent of that element in a variable
3. Remove the element from it's containing element

#### The innerHTML property

It is important to know that there are security risks associated with the innerHTML.

To **add** new content, you must follow these steps:

- Store new content as a string in a variable
- Select the element whose content you want to replace
- Set the element's innerHTML property to be the new string.

To **remove** new content, you must follow this step:

- set the innerHTML to an empty string

### Advantages and Disadvantages of updting HTML content

CODE | ADVANTAGES | DISADVANTAGES
-----|------------|---------------
document.write() | quick way to show beginners how content can be added to a page | only works when the page initially loads, if used after the page loaded it can overwrite the whole page, not add content or create a new page by mistake. Causes problems with XHTML pages.
element.innerHTML | can add a lot of markup using less code, is simple and faster than DOM manipulation when adding a lot of content | should not be used to add content that came from user, as it can cause high security risk, it is difficult to isolate single elements that you want to update within a larger DOM
DOM Manipulation | good for changing one element from a DOM fragment in between a lot of files. Doesn't affect event handlers, easily allows script to add elements | slower than innerHTML when wanted to change a lot of the content, you need to write more code for what you want to achieve

## The Problem Domain

The Problem Domain is the hardest part of programming to understand. The reason why problem domain is so hard, is because you can’t really see what you are trying to build very clearly. Programming is easy if you understand the problem domain; so if understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

1. Make the problem domain easier
2. Get better at understanding the problem domain
