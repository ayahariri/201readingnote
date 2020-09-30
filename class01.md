# INTRODUCTION TO HTML & CSS

## All about HTML

### Structure & Layout

This image showcases how the layout of your page should look like with the tags needed.
![HTML5 Layout](https://stuyhsdesign.files.wordpress.com/2016/05/yoko-html5.png)

The structure is the layout of your content on your site.

Headings are extremely important to guide your reader into the most important information first, to the rest.

Heading 1
TEXT
  Heading 2
    TEXT
   Heading 3
   TEXT

HTML uses *elements* to describe the structure of your pages.There are several different elements. Each element has an opening tag and a closing tag which are very important in for google to properly understand the rendered page.

On the other hand, *attributes* tell us more about the elements. They appear on the opening tag of the element and are made up of 2 parts:

   1. a name followed by
   2. a value seperated by an equal sign.

      **inline elements** will always appear to continue on the same line as their neighbouring elements. For example : < a >, < b >, < em >, and < img >.

      **grouping text & elements in a block** are used with the < div >, which allows you to group a set of elements together in one block-level box.

## Extra Markup

The following are the essential aspects one needs to learn in addition to the previous tags/elements;

- DOCTYPES tell browsers which version of HTML you are using.
- We also have the *headers* and *footers* are known as < header > and < footer >
- You can add comments to your code between the <!-- and --> markers.
- The < div > and < span > elements allow you to group block-level and inline elements together.
- The < nav > the navigation element
- < iframes > cut windows into your web pages through which other pages can be displayed.
- The < meta > tag allows you to supply all kinds of information about your web page.
- Escape characters are used to include special characters in your pages such as <, >, and ©.
- The ID attribute is used to uniquely identify that element from other elements on the page
- The navigation known as "< nav >" is used to contain in the major navigational blocks on the site
- Article "< article >" acts as a container for any section of a page that could stand alone and be modified later on.
- Aside "< aside >" is used usually in two ways:
     1. inside an "< article >" means it contains information that is related to the article, but not to it's overall meaning
     2. outside an "< article >" means it acts as a container that is related to the entire page
- Section "< section >" groups related content to one another.

## All about CSS

Before starting any project, a process needs to take place, where brainstorming and sketching the ideas are implemented.

### Process & Design

For this segment, we will be covering 3 major topics;

1. Building a site
2. Understanding your audience and their needs
3. How to present your information in an aesthically pleasing way

#### 1. Building a site

Asking questions is essential in order to gather up ideas and brainstorm to have a better mindset before entering the process and design of your site.
The following are types of questions that will help guide through your path;

- How to organize information that will be easy for your site visitors?
- What theme and layout should I use that will be visually comfortable for the audience?
- What are designs tips that I am not familiar with to gain my creativity?

#### 2. My audience & their needs

Note that your site will only be catered to your audience's needs and wants and nothing else.

How can I get to know my audience?

Brainstorming and writing key words is very important when it comes to design. You will have to create design solutions that will make the audience's experience enjoyable and desirable.

Is your audience:

- individuals
- companies

Writing down questions to understand a bit more deeply about your audience will also help you want pin point who they are;

- What are their ages?
- Where do they live?
- Marital status?
- Are they familiar with the web?
- How often do they use the web?

There are numerous questions to be asked, the more questions the narrower is your focal point. A survey might be a great help to widen your results.

Name | Gordon | Molly | Jasper | Ayo | Ivy |
-----|--------|-------|--------|-----|------
Gender | M | F | M | M | F
Age |  28 | 47 | 19 | 32 | 35

After understanding who your target audience really is, you can go deeper into understanding what they want and don't want, like and dislike about the web.

#### 3. Design of your site

The design is so important that even if the content was not relevant, the design of the site can make your audience think it is.

#### Site Maps

Site maping is basically sketching out the layout of your site. You can think of it as the skeleton body of your future site.

![Site Map Structure](https://blog.hubspot.com/hs-fs/hubfs/dyno-mapper-sitemap-generator.png?width=566&name=dyno-mapper-sitemap-generator.png)

##### Wireframes

A wireframe is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require.

![Wireframe Example](Screen Shot 2020-09-21 at 3.00.21 PM.png)

You will need to set the hierarchy of your content, by selecting the priorities, then organizing them

The hierarchy is achieved by focusing on the following aspects:

- Size:
Larger elements will grab users' attention first. For this reason it is a good idea to make headings and key points relatively large.
- Color:
Foreground and background color can draw attention to key messages. Brighter sections tend to draw users' attention first.
- Style:
An element may be the same size and color as surrounding content but have a different style applied to it to make it stand out.
- Visual:
Refers to the order in which your eyes perceive what they see. It is created by adding visual contrast between the items being displayed. Items with higher contrast are recognized and processed first.
- Grouping:
You can use grouping and similarity to help simplify the information you present.

A consitency in a design is very important in order to keep the design and typography visually presentable.

## More about CSS

CSS is the cascading style sheet that is responsible for how the web page will look like. It allows you to create rules that specify how the content of an element should appear.
We will cover the following topics below:

- How does CSS works?
- How to write CSS rules?
- How CSS rules apply to HTML pages

### How CSS works

As we previously mentioned, CSS is basically the styling sheet. Once we have our content, the designing part starts! The design is as important as the content.

CSS is a tool where you are in control to design every aspect of the content. The aspects are presented in 3 variables:

1. Boxes
2. Text
3. Specific.

These variables contain specifications that are controllable.

#### Boxes

Boxes refers to the Width and height, borders (color, width, and style),background color and images position in the browser window.

##### Text

Text is the typeface, which is the design of lettering that can include variations, such as extra bold, bold, regular, light, italic, condensed, extended, etc. We also have the size of the text, the color.

#### Specific

There are also specific ways in which you can style certain elements such as lists, tables, and forms.

## How to write CSS rules

CSS links the style rules we implemented with the HTML elements.
The rules govern how the content of specified elements should be displayed.
For example: [p
font-family: Bebas;]

You can add 2 properties to design under one aspect, such as;
[p
font-family: Bebas;
color:cyan;]

It is very important to remember to close the rule by adding a semi-colon.

If there are two or more rules that apply to the same element, it is important to understand which will take precedence. So if the two selectors are identical, the last of the two will take precedence. But if one selector is more specific than the others, the more specific rule will take precedence over more general ones.You can add !important after any property value to indicate that it should be considered more important than other rules that apply to the same element.

## How CSS rules apply to HTML pages

There are 3 different ways in which we can use the CSS;

1. Inline (it is just writing the CSS rule inside to the HTML tag. Will have to repeat yourself a lot of times, therefore it is not prefered to be used.)
2. External (creating a css file with all the styling rules, then linking it to the HTML file. When building a website there are several advantages to placing your CSS rules in a separate style sheet. All of your web pages can share the same style sheet.
3. Internal (creating an HTML page by placing the rules inside a < style > element, which usually sits inside the < head > element of the page.)

### What are CSS Selectors and how are they useful

There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document. CSS selectors are case sensitive, so they must match element names and attribute values exactly. Click for [more examples](https://farhad-hossain.com/farhad/public/assets/blogsImages/1562857201.png)

You can check my readme.md notes;[View link](https://ayahariri.github.io/Reading-Notes/Read05)

## How do computers work

### What makes a computer functioning

Throughout the years, we have always built tools in order to solve problems. Back in the days, these tools were were help for the manual labor, such as;

- a wheele barrel.

As years passed on, machine were invented in order to solve thinking labor, such as;

- solving equations.

In order to create a thinking machine, 4 tasks were needed to be done:

1. Input
2. Storage
3. Processing
4. Output

All 4 mentioned aspects are found in common in **ALL** computers.

#### 1. Input

The input takes what the user is currently doing on the computer (scrolling, clicking, etc)

#### 2. Storage & Processing

All the inputs are then stored in the memory (which is the storage). Then the computer's processor takes the information from the memory and manipulates it using *algorithms* into series of commands, then sends the information back to the stored memory again.

#### 3. Output

How a computer outputs information depends on what the computer's designed to do.

A computer display can show:

- text
- photos
- videos

### Hardware & Software

The hardware is the combination of different elemts inside a computer;

- circuits
- speakers
- wires
- chips

and the list goes on. And what we don't see, falls into the software category;

- example:  web pages.
The software in other words is what we do not see in a computer.

### How do hardwares and softwares interact with one another

#### 1. CPU

The central processing unit (CPU) is the master chip that controls all the other parts of the computer. It needs to do different things,so for this reason it has a wide range of simpler parts that handle specific tasks.

It contains:

- circuit to handle math and logic
- circuits to send information to and from different parts of the computer

#### 2. Binary Code

The binary code is the most basic form of software and controls all the hardware of a computer. (Programing Languages)

## Circuits & Logic

Circuits can sometimes be seen as art. Any creative idea in mind can be turned into a circuit.

Circuits are mini electronic components joined together.

*Simple circuit* take an electronic signal and then flip it this means if signla is 1, circtuit gives you a 0 and vis versa.
*complicated circuit* can take multiple signals and combine them, thus giving you a different result.  For this example, a circuit would take 2 electrical signals (same or different), the results will still be a 0, unless both are 1 and 1.

## The Realm of Javascript

Being able to change the content of an HTML page while it is loaded in the browser is very powerful. The examples below rely on the ability to:

- Access the content of the page
  - Modify the content of the page
    - Program rules or instructions the browser can follow
      - React to events triggered by the user or browser

Before stepping into the realm of programming, we first need to learn the ABC's of the language itself.
A. What is a script and how do I create one?
B. How do computers fit in with the world around them?
C. How do I write a script for a web page?

***A. What is a Script?***
A script is a series of instructions that a computer can follow to achieve a goal. In order to write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it. You can use the following to simply your goal:

1. **DEFINE THE GOAL**
2. **DESIGN THE SCRIPT** by splitting the goal out into a series of tasks that are going to be involved in order to execute what is in mind.
3. **CODE EACH STEP** each of the steps needs to be written in a programming language (JavaScript) that the computer understands. (Vocabulary & Syntax are very important to learn).

- Flowcharts are a good tool to create to work out how the tasks fit together. The flowcharts show the paths between each step.

***B. How do computers fit in with the world around them?***

In Javascript or any computer programming, the focus is on 2 things:

OBJECTS (THINGS) | PROPERTIES (CHARACTERISTICS)
----|------
Each object have their own properties, events * methods | Each property has a name, value, and each of these name/value pairs tells you something about each individual instance of the object

### How can people interact with objects

There are common ways in which people interact with each type of object.

- An event is the computer's way of sticking up its hand to say, "Hey, this just happened!" After, that event can be used to trigger a specific section of the code.
- Methods typically represent how people (or other things) interact with an object in the real world. The code for a method can contain lots of instructions that together represent one task.

***C. How do I write a Script for a web page?***

A JavaScript fi le is just a
text file (like HTML and CSS filesare)butithasa.jsfile extension, so save this file with the name add-content.js

When you want to use JavaScript with a web page, you use the HTML < script > element to tell the browser it is coming across a script.
Its sre attribute tells people where the JavaScript file is stored. This is basically linking the JS onto the HTML such as:

<!DOCTYPE html>
<html>
<head>
<title>Constructive &amp; Co.</ title>
<link rel ="stylesheet" href="css/ cOl.css" />
</ head> <body>
<hl>Constructive &amp; Co.</hl>
<script src="js/ add-content.js"></ script> <p>For all orders and inquiries please call
<em>SSS-3344</ em></ p> </ body>
</html>