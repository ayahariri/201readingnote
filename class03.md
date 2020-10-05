# Lists & Boxes in HTML & CSS

## Lists (HTML)

HTML provides us with four different ways to display content:

- Ordered Lists < ol >
  - Unordered Lists < ul >
    - Definition Lists < dl >
      - Nested Lists (adding second list inside first)

    Each list type contains items known as < li >, as sees on the table below:

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

![Border, Margin & Padding ](https://sabe.io/classes/css/css-box-model-padding-border-margin/css-box-model.png)