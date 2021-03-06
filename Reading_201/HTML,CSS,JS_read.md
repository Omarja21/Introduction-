 linking to other sites:
<a href='https://www.google.com'>Google</a>

so this is the basic structure for linking tag and it is called anchor tag, and by using it you can refer for other 
websites in your page, so in the example above we can see that we refer to the google website in the href='' part
and what appears on the user screen is what you type inside the tag.

also you can you can use the <a> tag to refer for another page in you project such as home page about us page and so on 
using the same method is refering for a website 

another way of using the <a> tag is to link a specific with a word of your choice to send an email when it is clicked 
<a href='example@example.com'>mail us</a>
one of the best features in html when writing a link is the ability to open a link in new tab for example
<a href='www.google.com target="_blank">tap here to get into google in new tab </a>

The final feature of the links in HTML is that you can link a specific part of the page with another in the by giving the 
same page by using the id for example:
<a href="#test">paragraph 1</a>
<p id="test">content of the paragraph</p>
so when you click on the paragraph 1 it will take you to the paragraph with the same id of "test" in the same page.

positioning in CSS
 there is several positioning ways in CSS: 
1-the first one is the default one which is static positioning where each block-level element sits on the top of the next one 
position: static;
2-the second one is relative positioning which is simply where you want to move the block-level element from its 
default position from the 4 sides:
position: relative;
left: 100px;
top: 50px;
so it will move to the right for 100px and to the bottom for 50px
3-the third type of positioning is absolute positioning and what you can benifit from this kind of positioning is that the 
element that is given a absolute positioning it will act and position where ever you like and will deal with other elements aas if 
they are not visible 
position: absluote;
4-the fourth type of positions is fixed which is type of the absolute position but the fixed element will stay on the screen 
even if the user scrolls up and down and the most common use for it is the heading of the web page
position: fixed;
5- the fifth one is z- index which is used for overlaping elements, so this positioning is related to the previous one
when you determine a fixed position element the browser will make the elements that comes later on top on the element 
that came first so in order to manage what to appear on top of what you can use:
z- index: 10; /// note that the more the value the more the element is close to the top 
6-The float property allows you to take an element in normal flow and place it as far to the left or right of the containing
element as possible.
Anything else that sits inside the containing element will flow around the element that is floated.
position: float;
width: 200px;

the truthy and falsy values:
-fasly?
falsy values for the variables:
boolean false
0
empty string
undefined
not a number (NaN)
truthy values for the variables:
true
1
"carrot"
10/5
"0"
"false"

if (condition){
	statment;
} else if(condition){
statment;
} else{
}
this is used to control the flow
x==y checks for the value
x===y checks for data type and value

switch statment:
switch:
switch value:
case value: statment 1
case value: statment 2
default: statment x
example1:
let userName = 'yahya';
switch userName{
case 'yahya':
		log('hello');
break; ==> to tell the  go out side the switch if the statment was correct
case 'YAHYA':
		log('hello again');
case 'yahia':
		log('hello with I');
default:
	log('not authenticated');
}

loops:
	1-for(initializer;condition;update){
satatment
}
example:
we want to count numbers
for(let i=0; i<=10; i++){
	//console.log(i)
	let element = '<h3>'+i+</h3>;
	document.write(element);
}
2- while (condition){
performthis task;
}
Example:
	let userName=prompt('pls provide username');
	while(!userName){
	//! ==> means not meeting the condition
userName=prompt=('you must provide an input');
}
alert('hello '+ userName);
3- do while loop
	do{
	  statment;
}	while(condition);

Arrays: it is another data type to preserve more that one values in one place
print 5 different types of fruits in consol log
The syntax of array:
let fruitsList=[];
example:
let fruitsList=['apples', 'grabes', strawberries'];
let studentMarks=[20, 15, 18, 19]
let ages=[20, 30, 35, 19]
address     0   1   2   3
each element inside of the array have address and it is called index
let fruits=['apples', 'oranges'. 'pinapples', 'cucumber'];
consol.log(fruit);
if we want to recal the oranges we type:
console.log(fruites[2])
//number 2 is the index
fruit.push('tomato'); //this command will add an item to the array
fruit.pop(); // to remove the last element of the array
fruits.shift(); // to remove an element for the beggining of the array
fruits.unshift('watermelons'); // to add element to the beggining of the array
fruits.indexOf('oranges') //to know the index of an element
type of: to check the data type of an element
casting is the operation of converting a data type into another.
