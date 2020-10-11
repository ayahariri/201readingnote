# All about Domain Modeling in JavaScript & Tables on HTML/CSS

## Domain Modeling (Functions, Methods and Objects) Javascript

Domain modeling is the process of creating a model in code related for a specific problem. The model describes several entities:

- their attributes
- their behaviours
- the constraits that govern the problem domain.

A proper structured domain model can verify and validate the understanding of specific problems.

[Domain Modeling Example](https://github.com/codefellows/domain_modeling#domain-modeling)

### How memory and variables work

Each variable that is declared takes up memory. The more variables a browser has to remember, the more memory your script requires to run. Scripts that require a lot of memory can perform slower, which in turn makes your web page take longer to respond to the user.

Objects group together a set of variables and functions to create a model of something you would relate to with the real world.  In an object, variables and functions tak up new names. In an object:

- variables are known as *properties* (such as name, type of, number of and so on. )
- functions are known as *methods* (methods represent tasks that are associated with the object.)

### Creating an object (literal notation)

#### Literal Notation

Althought there are several ways to create opbjects, literal notation is the easiest and most common way.
var hotel = {
    name: 'FourSeason',
    rooms: 60,
    booked: 25,
    checkAvailability: function () {
        return this.rooms - this.booked;
    }
};
In this case, 'hotel' is the object, name, rooms and booked are properties and the last line is the method of what should be calculated (here the number of available rooms.)

#### Dot Notation

You can access the properties of an object by square brackets or like methods, by the dot notation.
var hotelName = hotel.name;
var roomsFree = hotel.checkAvailability();

#### Constructor Notation

You can first create a blank object, then add properties and methods to the object.
var hotel =  new Object();
**hotel.name = 'FourSeasons';**
**hotel.rooms = '60';**
**hotel.booked = '25';**
*hotel.checkAvailability = function() {*
    *return this.room - this.booked;*
};
In bold are the properties, and in italic is the method.

To update the value of properties, use *dot notation* or *square brackets*.
hote.name = 'Park';
To delete a property, use the **delete** keyword.
hotel['name'] = 'Park';

You can also create multiple objects, to represent similar things for example, by using a function as a *template*.
function Hotel (name, rooms, booked) {  
this.name = name;
this.rooms =rooms;
this.booked = booked;
this.checkAvailability = function() {
return this.rooms - this.booked;
};
}

### REFRESH/MEMORY Storing Data (Variables and Arrays)

In JavaScript, data is represented using name/value pairs.
To organize your data, you can use an array or object to group a set of related values. In arrays and objects the name is also known as a key.

So an object would go for
costs = {
    room1: 420,
    room2: 340,
    room3: 230,
}
But in an array, it would be like this
costs = [420, 340, 230];

Arrays in an object | Objects in an array
--------------------|---------------------
The property of any object can hold an array such as costs.room1.items[0]; | The value of any element in an array can be an object. costs[2].phone;

#### Built-in Objects

Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window. These built-in objects act like a toolkit for creating interactive web pages.

The difference between document model and global javascript objects are seen on the bellow picture respectively:
![Document Object Model](https://static.javatpoint.com/images/javascript/dom.jpg)
![Global JavaScript Objects](https://i.stack.imgur.com/qG4DR.png)

The Math object has properties and methods for mathematical constants and functions:

Property | Description
----------|-------------
Math.PI | Returns pi (to it's approximate)
Method | Description
-------|--------------
Math.round() | Rounds number to the nearest integer
Math.sqrt(*n*) | Returns square root of positive number,e.g.,Math.sqrt(9) returns 3
Math.ceil() | Rounds number up to the nearest integer
Math.floor() | Rounds number down to the nearest integer
Math.random() | Generates a random number between 0 (inclusive) and 1(not inclusive)

## Tables on HTML/CSS

A table represents information in a grid format. Tables are essential in displaying content such as results, or disadvantages/advantages, or comparing one thing to the other, so on and so forth. *Grids* allow us to understand long and complicated data by referencing information on two axes.And each block in the grid is referred to as a *table cell*.

A basic table structure goes by:

1. < table > ; used to create a table
2. < tr > ; indicate the start of each row (tableRow)
3. < td > ; represents each cell of a table

Some add a heading (title) to their table with the < th > tag. You can also use the spanning columns but opening and closing a < th > where you want space, or if content is long and want to add a bigger column use < td colspan="numberOfColumsToTake">. Same goes for the rows but instead of colspan, we use rowspan < td rowspan="numberOfRows" >. If the table was super long, you can seperate/organize your elements by using the following:

- < thead > ; where the headings should be in
- < tbody > ; where the body should be in
- < tfoot > ; where footer should be in.

For more visibility for the reader, you can control the spacing and width of your cells/rows/table: < table width="400" cellpadding="10" cellspacing="5">. Or even create a border and background: < table border="2" bcolor="black" >.
