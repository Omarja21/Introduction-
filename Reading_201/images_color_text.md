# Images 
### In this summary we will learn about how to add images into pages, and their right format and how to optimize images for the web site.

#### First before learning how to add images, and for better ordering for your work, you need to creat a folder in your project files called images so you can put all you images, logos, buttons and so on.
#### after doing so you can add images by using the \<img\> tag by and as the img tag is self closing tag you can includ the source of the image inside of the tag such as <img src="img.jpg" alt="this is a description of the image in case of the image did not appear" title="title will appear when you hover over the image for further description about the image'>
#### also you can use the 'hight' and 'width' inside of the img tag.
#### Now after doing all that for the image you need to know how to place the image inside of your code, so when put the image befor the <p> tag the text of the paragraph will appear on a new line after the image, but if you positioned the image inside of the begining of the <p> tag the image will appear before the text but the first part of the text will align with the bottom of the image , and last if you write the image tage in the middle of the <p> tag the image wil appear in the middle of the text, also you can use the align attribute (left or right) to pick where to place the image inside of the paragraph, further more you can use the align property ,inside of paragraph, (top, middle ,bottom) to align the photo with the text, for example top: to align the first line of the text with the bottom of the photo, middle: to align the first line of the text with the middle of the photo, bottom: to align the first line of the text with the bottom of the text.
#### There are three fundimental rules for creating an image which are:
 1- save image in the right format
 2- save image in the right size 
 3- use the correct resolution
 #### finally you can use the <figure> to include a photo that you need to write a breif description below it and <figcaption> inside of the figure tag to write the description for the photo and that description will appear below the photo.
 ==============================================================================================================================================
 # color
 #### In this summary we will talk about how to specify a colors and how to choose the background color.

#### In CSS you can set the color of the desirable element (color of the text, background color, border...and so on) by using three methods:
1- RGB valus
2- hex codes
3- color names 
#### Also we need to understand that every color on the screen are made of three main colors which are RED, GREEN and BLUE.
#### also you need to know three main terms for further understaning of colors which are:
* hue: which is the the color it self
* saturatoion: the amount of grey in color
* brightness: the amount of blackness in color
* contrast: the diifernce in brightness between the background and the foreground of a image, text and what so ever( for example the higher is better for readability of text)
* opacity: the transperancy of the image(it is mesaured between 0 and 1)
================================================================================================================================================
# Text
#### In this summary we will get to know some of the text properities and how they are used:
* font-family: The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.
* font-face:e allows you to use a font, even if it is not installed on the computer of the person browsing, by allowing you to specify a path to a copy of the font, which will be downloaded if it is not on the user's machine.
* font-weight: The font-weight property allows you to create bold text. There are two values that this property commonly takes:
1- normal
2- bold
* text-transform: The text-transform property is used to change the case of text giving it one of the following values:
1- uppercase
2- lowercase
3- capitalize
* text-decoration: The text-decoration property allows you to specify the following values:
1- none
2- underline
3- overline
4- line-through
5- blink
* line-height
* letter-spacing, word-spacing
* text-align: The text-align property allows you to control the alignment of text. The property can take one of four values:
1- left
2- right
3- center
4- justify
* text-indent: This property allows you to indent the first line of text within an element. 
* text-shadow: it is used to drop a shadow behind a text
* link: This allows you to set styles for links that have not yet been visited. 
* visited This allows you to set styles for links that have been clicked on. 
* hover: this is used to identify the elements that are hovered over by the users mouse 
