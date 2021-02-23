How the java script intorregate with HTML and CSS
This is where the content of
the page lives. The HTML gives
the page structure and adds
semantics.

The CSS enhances the HTML
page with rules that state how
the HTML content is presented
(backgrounds, borders, box
dimensions, colors, fonts, etc.).

This is where we can change
how the page behaves, adding
interactivity. We will aim to keep
as much of our JavaScript as
possible in separate files.


Java script line: 
var today= new Date();
var hourNow = today.getHours();
var greeting;
if (hourNow > 18) {
greeting= 'Good evening!';
else if (hourNow > 12) {
greeting = ' Good afternoon!';
else if (hourNow > 0) {
greeting = 'Good morni ng!';
else {
greeting = 'Welcome! ' ;
document .write( ' <h3>' +greeting + ' </ h3> ');

<body>
<script src="js/ add-content.js"></ script>
</body>

Statment
A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon. 
Statments:
var today= new Date{);
var hourNow = today.getHours{) ;
var greeting; 

COMMENTS:
You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code. 
// Display the appropriate greeti ng based on the current time
MULTI-LINE COMM ENTS:
*/ characters.
Anything between these characters is not processed·
by the JavaScript interpreter.
M ulti-line comment s are often used for descriptions
of how the script works, or to prevent a section of
the script from running when testing it. 

WHAT IS A VARIABLE?
A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables. 

A variable is a good name for this
concept because the data stored
in a variable can change (or vary)
each time a script runs. 

How to declare variables 
Var x;
How to assign variables
Var x= 3;

DATA TYPES 
there are 3 types of data in JS 
NUMERIC DATA TYPE
The numeric data type handles
numbers.
0.75 
STRING DATA TYPE
The strings data type consists of
letters and other characters.
'Hi, Ivy!'
BOOLEAN DATA TYPE
Boolean data types can have one
of two values: true or false.
true 

USING A VARIABLE TOSTORE A NUMBER:
var price;
var quantity;
var total;
price = 5;
quantity = 14;
total = price * quantity;
c02/j s/numeri c-vari ab 1 e .j s
var el = document.getElementByid( ' cost ');
el .textContent = '$' +total; 

USING A VARIABLE TO STORE A STRING:
var username;
var message;
username = 'Molly';
message = 'See our upcoming range';
var elName = document.getElementByld{'name');
elName .textContent = username;
var elNote = document .getElementByld( 'note');
elNote .textContent = message; 

