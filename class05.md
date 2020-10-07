# Using Images, Forms & Text on HTML & CSS

## Images on HTML & CSS

Images are important to be added on your webpage for many reasons such as including any image, logo, photograph, illustration, etc.It is better to store the chosen images on your site. You will need to use the following tag:

1. Add an image:
< img src="imagefolder/imagename.jpg" alt="describtion of image" title="title for the image." />
2. Choose the height and width:
< img src="imagefolder/imagename.jpg" alt="describtion of image" *width*="600" *height*="450" />
3. Placement of the image:
where you place the code is basically where the image would show.
4. You can align your image to the left or right:
< img src="imagefolder/imagename.jpg" alt="describtion of image" *width*="600" *height*="450" alight="leftOrRight"/>

*It is preferable to save the image you want to use as the size you will want it on your website. You need to also make sure it is a high resolution image in order to avoid any pixelations. Bad images can ruin the feel of the website. Adding transperency is also useful in the design aspet (UI/UX).*
5. You can show a title under or above the image inside the < figure > < / figcaaption > by using < figcaption > </ figcaption >

**How to check image sizes from the browser?**

Open the image on a new tab (chrome), the size of the image appears on the title of new tab.

## Forms on HTML & CSS

Forms are like the search bar/box on google's homepage. There are several types of form control that you can do to collect information from the visitors of your site:

1; **Adding Text**

- Text Input {single line purposes, i.e emails.}
- Password Input {also a single line but characters are masked.}
- Text Are {multi lines, i.e messages/comments.}

2; **Making Choices**

- Radio Buttons {when user must select one button out of many options.}
- Check Boxes {to select or unselect more than one option.}
- Drop-Down Boxes {picking one of a number of options from a list.}

3; **Submitting Forms**

- Submit Buttoms {to submit data from your page to another.}
- Image Buttons {same but allow you to use an image.}
- Uploading Files {allow users to upload files to a website.}.

*Syntax of a form (Structure)* < form action="url" method="get" >

### Text Input

The **inoput** tag is used to create several different form controls like:

- < input *type*="text" /> ; which allow you to create your text into a single-line text input.
- < input *name*="username" /> ; allow you to name what the server will be entered with.
- < input *maxlength*="30" /> ; allow you to limit the number of characters a user may enter.
- < input *size*="15" />

### Password Input

- < input *type*="password" /> ; which allow you to create your password into a single-line text input.
- name, size and maxlength can also be used, as we did in the *input text*.

### Text Area

The text area element is used to create a mutli-line text input and will appear in a text box. < textarea > < / textarea >

### Radio Buttons

- < input *type*="radio" /> ; which allow you to create your password into a single-line text input.
- name, is also be used, as we did in the *input text*.
- value="pop"; value="rock" and so one, will indicate the value that is sent
- checked="checked" is used to indicate which value should be selected when the page loads.

### Check Box

- < input *type*="checkbox" /> ; which allow you to select one or more answers to a question.
- value, name and checked are used as we did in the **radio buttons**.

### Drop Down List Box

- < select name="devices" > ; the select tag allow users to select an option from many from a drop down list, and the name will indicate the name of the form control being sent to the server.
- < option value="ipod" >iPod < / option > ; the *option* is used to speficy the option user can select from, and the *value* will indicate the value seen.
- You can allow users to select multiple options from the list by adding the < multiple="multiple" >

## Text on HTML and CSS

There are 3 ways to display a font (typeface terminology):

1. Serif
2. Sans-Serif
3. Monospace

We can go deeper in the design and control the weight (light - medium - bold - black ) or the style (normal - italic - oblique ) and the stretch of it (condensed - regular - extended)

### Text Syntax

- font-family ; to choose the font (serif, sans serif or monospace) (for more font choices @font-face then the source and format)
- font-size ; to determine the size of your text/font (either in pixels, % or ems)
- font-weight ; to be able to bolden a text
- font-style ; to picl if it's normal, italic or oblique
- text-transformation ; to make a text uppercase, lowercase or capitalized.
- text-decoration ; to create either no decoration none, or an underline, overline, line-through or blink.
- letter-spacing, word-spacing ; is the kerning of each letter or word with one another
- text-align ; to be able to align your paragraph/text to the left, right, center or justify. Justify indicates that every line expect the last should be set to the up the full width of box.
- vertical-align ; allow you to vertically align text in the middle of the block level element.
- text-indent ; allow you to indent the first line of text within an element.
- text-shadow ; allow you to create a shadow effect, all sides must be mentioned)
- :link, :visited ; allow you to set styles for links that have not been visited, and visited will allow you to create a style for when link is visited.
