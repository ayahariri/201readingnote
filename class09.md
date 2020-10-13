# Forms, Lists & Table on HTML/CSS & Events on JavaScript

Whether you are adding a simple search box to your website or a contact us fill-in section, HTML forms give you a set of elements to collect data from The best known example *form* on the web is probably the search box that sits right in the middle of Google's homepage.

There are several types of form controls that you can use to collect information from visitors to your site.

**To add text:**

- Text input (single-line)
- Password input (characters are masked, single line)
- Text area (for longer texts, like comments or message)

**To make choices:**

- Radio buttons (to select one from number of options)
- Checkboxes (to select/unselect one or more options)
- Drop-down boxes (select one or more options from a drop-down list)

**To submit forms:**

- Submit buttons (to submit data from your form to another i.e subscribe)
- Image buttons (allow to use an image to submit data)

**To uploading files:**

- File Upload (allow user to upload files to a website)

## Form Syntax

< form > always carries the action attribute and usually has a method and an id attribute. The form tag has form controls inside of it:

- *action* is the URL for the page on the server that will recieve the information, so < form action="url" >
- *method* can either be get or post. With the get method, the values from the form are added to
the end of the URL specified in the action attribute.With the post method the values are sent in what are known as HTTP headers. < form action="http://www.example.com/subscribe.php" method="get/post" >

< input > is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating.

### Text Input Syntax

- *type="text"* When the type attribute has a value of text, it creates a single- line text input.
- *name* When users enter information into a form, the server needs to know which form control each piece of data was entered into. < input type="text" name="username" / >
- *size* The size attribute should not be used on new forms. It was used in older forms to indicate the width of the text input (measured by the number of characters that would be seen).< input type="text" name="username" size="15"/ >
- *maxlength* You can use the maxlength attribute to limit the number of characters a user may enter into the text field. < input type="text" name="username" size="15" maxlength="30" / >

### Password Input Syntax

- *type="passowrd"* When the type attribute has a value of text, it creates a single- line text input.
- *name* When users enter information into a form, the server needs to know which form control each piece of data was entered into. < input type="text" name="username" / >
- *size* The size attribute should not be used on new forms. It was used in older forms to indicate the width of the text input (measured by the number of characters that would be seen).< input type="text" name="username" size="15"/ >
- *maxlength* You can use the maxlength attribute to limit the number of characters a user may enter into the text field. < input type="text" name="username" size="15" maxlength="30" / >

< Text Area > is used to create a mutli-line
text input. Unlike other input elements this is not an empty element.

### Radio Button & Checkbox

- *type="radio/checkbox"* < input type="radio"  />
- *name* is sent to the server with the value of the option the user selects. < input type="radio" name="genre" />
- *value* indicates the value that is sent to the server for the selected option. < input type="radio" name="genre" value="rock" />
- *checked* You can use the maxlength attribute to limit the number of characters a user may enter into the text field.  < input type="radio" name="genre" value="rock" checked="checked" />

### Drop Down List & Multiple Select box

- < select > A drop down list box (also known as a select box) allows users to select one option from a drop down list along with the **name attribute**.
- < option > is used to specify the options that the user can select from along with the **value attribute**.
- You can allow users to select multiple options from this list by adding the multiple attribute with a value of multiple. (*multplie select box*)

If you want to create a single line text box for search queries, HTML5 provides a special type of input for that purpose, use the following tags:

- type="search"
- placeholder="Enter Keyword" (to show text written in search bar in low opacity)

## Lists on HTML & CSS

The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker).It can be used on rules that apply to the < ol >, < ul >, and < li > elements. The list types are the following:

- decimal
- decimal-leading-zero
- lower-alpha
- upper-alpha
- lower-roman
- upper-roman

Lists are indented into the page by default and the list-style- position property indicates whether the marker should appear on the inside or the outside of the box containing the main points. This can take one of these two values :

1. outside (default)
2. inside (The marker sits inside the box of text (which is indented).)

## Tables on HTML & CSS

You can create an empty cell on a table by using the following property and attributes under whatever needs to be changes (table, td, tr, th, etc)

- empty-cells: show; shows the borders of any empty cells.
- empty-cells: hide; hides the borders of any empty cells.
- empty-cells: inherit; if you have one table nested inside another, the inherit value instructs the table cells to obey the rules of the containing table.

You can also create gaps between cells by using (border-spacing: or border-collapse) with the collapse or seperate attributes

## What are Events on JavaScript

When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.

We have interactions that create events, then events trigger code and finally code responds to users. There are several event types, as shown below:

Event | Definition
------|-----------
load | web page gas finished loading
unload | web page is unloading
error | browsers found JavaScript errors
resize | browser window has been resized
scroll | user has scrolled up or down the page.

When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code. The *event handling* steps go as follow:

1. Selecting the element node you want the script to respond to
2. Indicate which event on the selected node(s) will trigger the response.
3. State the code you want to run when the event occurs.

### Event Flow

HTML elements reside insde other elements. If you hover or click on a link, you will also be hovering or clicking on its parent element.
Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon. You can also use event delegation to monitor for events that happen on all of the children of an element.
