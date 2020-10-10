# Javascript Functions & HTML Dom Tree

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


## The Problem Domain

The Problem Domain is the hardest part of programming to understand. The reason why problem domain is so hard, is because you can’t really see what you are trying to build very clearly. Programming is easy if you understand the problem domain; so if understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

1. Make the problem domain easier
2. Get better at understanding the problem domain
