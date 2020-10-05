# Lists, Boxes, Borders & their design in HTML & CSS

## Lists (HTML)

HTML provides us with four different ways to display content:

- Ordered Lists < ol >
  - Unordered Lists < ul >
    - Definition Lists < dl >
      - Nested Lists (adding second list inside first)

    Each list type contains items known as < li >, as seen below:

    Example for *Ordered List*:

< ol >
 < li > ITEM < / li >
 < li > ITEM2  < / li >
< / ol >

    Example for *Unordered List*:

< ul >
 < li > ITEM < / li >
 < li > ITEM 2 < / li >
< / ul >

    Example for *Definition List*:

< dl >
 < dt > **definition term 1** < / dt >
  < dd > **definition 1** < / dd >
 < dt > **definition term 2** < / dt >
  < dd > **definition 2** < / dd >
< / dl >

    Example for *Nested List*:

< ul >
 < li > TEXT < / li >
 < li > TEXT 2
   < ul >
      < li > SUBTEXT 1 < / li >
      < li > SUBTEXT 2 < / li >
< / ul >
 < / li >
 < li > SUBTEXT 3 < / li >
 < / ul >

## Boxes (CSS)

Boxes are basically how CSS treats each *HTML element* as if they were inside a box. There are properties that affect the appearance of these boxes, which are.

### Box Dimension (widht,height)

The size of the box is already set by default to fit the content. To manage and control it's size, **the height property* and *width property* come in hand.

There is also a property to limit the width and height, which go by (respectively)

- "min-width" and "max-width"
- "min-height" and "max-height"

In case of an of extra content, the overflow property is used to either hide the content or make it scrollable, such as:

- "overflow: hidden;"
- "overflow: scroll;"

### Border, Margin & Padding

Every box has several properties that can be adjusted to control the way it looks, such as the picture below:

![Border, Margin & Padding ](https://sabe.io/classes/css/css-box-model-padding-border-margin/css-box-model.png)

#### BORDER

You can control their display and looks by using different property which goes for:

- border-width: You can be more specific by using the sides as a seperate property:
   border-top-width OR border-bottom-width OR border-right-width OR border-left-width
- border-style: You can be more specific by selecting the style:
   border-style: solid; one line
   border-style: dotted; dotted line
   border-style: dashed; short lines line
   border-style: double; two lines
   border-style: groove; carved effect
   border-style: ridge; sticking out of frame
- border-color: You can specify which side to be which color by:
   border-top-color OR border-bottom-color OR border-right-color OR border-left-color

   There is a simpler way to display all the properties under one property. For example:

p {
    border: 3px dotted white;}

- border-image: You can apply an image to the border of any box ; border-image: url("")
- border-radius: Creating rounded corners

#### MARGIN & PADDING

*Padding* and *Margin* are properties that help you add space around the element in question.

The **padding** property allow us to control how much space is between the content of an element and it's *border* --> "padding: ;"

The **margin** property controls the gap between boxes. --> "margin: ;" You can center a box on the page or inside the element by setting the *left-margin* and *right-margin*

The *display* property allows you to control it's display:
   display: inline;
   display: block;
   display: inline-block;
   display: none;

   You can add a *shadow effect* by using the property box-shadow by applying the horizontal, vertical offset and the blur distance and spread of shadow. Example: box-shadow: 5px 5px 5px black;

## How to use JavaScript

### Variables

There are several ways to utilize variables in Javascript:

1. To store a Boolean such as
2. Shortcuts for variables
3. Changing the value of a variable

### Comparing Expressions

Javascript allow us to compare two or more different expressions by using:

- *comparison operators* usually return single values of **true** or **false**. [More about operators!](https://ayahariri.github.io/201readingnote/class02)
- *if statements* check a condition, and depending on the answer will go to second code block.
- *switch statements* must first start with a switch value, then cases that indicate a possible value for this variable and which code should run if variable matches value.
- [*true and false values*](https://www.sitepoint.com/javascript-truthy-falsy/)

### Checking a Condition

**Loops** check if a condition turns *true*, a code block will run. It will keep running until the return is *false*.