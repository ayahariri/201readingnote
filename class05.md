# Using Images & Forms

## Images on HTML & CSS

Images are important to be added on your webpage for many reasons such as including any image, logo, photograph, illustration, etc.It is better to store the chosen images on your site.

**On HTML** you will need to use the following tag:

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
