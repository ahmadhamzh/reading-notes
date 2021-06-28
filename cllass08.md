## Layout :
----------

- CSS treats each HTML element as if it is in its 
own box. This box will either be a block-level
box or an inline box.
- Block-level elements start on a new line.

           Examples include:<h1> <p> <ul> <li>
- Inline elements flow in between surrounding text .
 
           xamples include: <img> <b> <i>

- If one block-level element sits inside another 
block-level element then the outer box is 
known as the containing or parent element.

- CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute 
positioning. 
- Normal flow :

  Every block-level element appears on a new line, causing each item to appear lower down 
the page than the previous one.

- Relative Positioning :

  This moves an element from the position it would be in normal flow, shifting it to the top, right, 
bottom, or left of where it 
would have been placed.

- bsolute positioning :

   his positions the element in relation to its containing element. It is taken out of 
normal flow, meaning that it does not affect the position of any surrounding elements 
(as they simply ignore the space it would have taken up).

- To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom 
and left or right it should be placed.

- Fixed Positioning :

  This is a form of absolute 
positioning that positions 
the element in relation to the 
browser window, as opposed 
to the containing element.

- Floating Elements:

  loating an element allows you to take that element out of normal flow and position 
  it to the far left or right of a 
  containing box.

- Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

- Resolution refers to the number of dots a screen shows per inch.

- Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide 
(since most users will be able to see designs this wide on their screens).

- Fixed width layout designs do not 
change size as the user increases 
or decreases the size of their browser window. 
Measurements tend to be given in pixels.

- Liquid layout designs stretch and contract 
as the user increases or decreases the 
size of their browser window. They tend to 
use percentages.
-----
-----
refrences :

 From the Duckett HTML book:

  - HTML/CSS book, Ch. 15, “Layout”