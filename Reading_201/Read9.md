# forms
## In todays summary we will talk about an interisting topic that is talking about how to to collect information from visitors 
and the different kinds of form controls.
#### There are many types of forms such as the adding text forms:
* text input 
* password input
* text area 
#### The making choices forms such as:
* Radio buttons 
* check boxes 
* drop-down boxes 
#### The submitting forms: 
* submit buttons 
* Image buttons 

### Form structure:

<form action="http://www.example.com/login.php"
method="get">
<p>
 Test for form 
<p>
</form>
==============
<form>: Form controls live inside a <form> element
action: ts valueis the URL for the page on the server that will receive the information in the form when it is submitted.
method: Forms can be sent using one of 
two methods: get or post(whether you want to retrive or sent information from the server)

### Text input:
<form action="http://www.example.com/login.php">
<p>Username:
 <input type="text" name="username" size="10" 
 maxlength="15" />
</p>
</form>

The <input> element is used to create several different form controls.
type="text": When the type attribute has a value of text, it creates a singleline text input.
name: it is used to let the server know which form control the data was entered into
maxlength: You can use the maxlength
attribute to limit the number of characters a user may enter into the text field.

### password input 
<form action="http://www.example.com/login.php">
<p>Password:
 <input type="password" name="password" size="12" 
 maxlength="18" />
</p>
</form>
type="password":  it creates a text box that acts just like a single-line text input, except the characters are blocked out.
name:The name attribute indicates the name of the password input to send to server.
size, maxlength:It can also carry the size and maxlength attributes like the the single-line text input.

### there is also different type of forms such as:
* Text area: The <textarea> element is used to create a mutli-line text input
* Radio button: Radio buttons allow users to pick just one of a number of options.
* check types: Checkboxes allow users to select (and unselect) one or more options in answer to a question.
* drop down list:  allows users to select one option from a drop down list
* Multple select box: You can turn a drop down select box into a box that shows more than one option by adding the size attribute
* File Input Box: to allow the user to upload different type of files 
* submit button: The submit button is used to send a form to the server.
* Image Button: If you want to use an image for the submit button, you can give the type attribute a value of image using the src attribute.
* Grouping Form Elements: using the <fieldset> you can related form controls together inside the <fieldset> element. This is particularly helpful for longer forms
===========================================================================================================================================
# lists, Tables and Forms 
### In this summary you will learn about how to specify bullet point style, how to add borders and backgrounds to the table and how to change the appearence of orm elements
#### First  you need to know the bullet point styles for the unordered lists list-style-type in the css file and you can use these different styles:
*** decimal, decimal-leading-zero, lower-alpha, upper-alpha, lower-roman, upper-roman
#### also you can style the unordered list using an image of yours using this method: 
*** ul {list-style-image: url("images/star.png");} 
### Also you can adjust the marker of the list by using the: 
*** list-style-position: inside OR outside
### There are some properties that can be used with the tables to style them which are: 
* width, padding, text-transform, letter-spacing, font-size, border-top, border-bottom, text-align, background-color, :hover  
* you can use the empty-cells property to show or hide the the empty cells
* border-spacing: these properties are used to allows you to control the distance between adjacent cells
*, border-collapse: Borders are collapsed into a single border where possible.
