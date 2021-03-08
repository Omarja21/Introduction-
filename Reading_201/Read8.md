# Layout
### In this summary we are ging to talk about how to control the position of element, creating site layout, and the designing for different type of screens.
### first you need to recognize some key Key Concepts in Positioning Elements:
* building blocks: which are 2 types: block level(h1,p,ul,li) and in-line elements(img,b,i).
* containing elements: it is the where outer block element is the parent of insider block element
* controling the position of element in CSS:
 
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
