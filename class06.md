#  *Duckett JAVASCRIPT & JQUERY BOOK :*

## Object Literals :

- Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names. 

- literal notation is the easist and most popular way to creat an objects.

- you accsess the properties or methods of an opject using dot notation or squer brackets.

## Document Object Model :

- The Document Object Model (DOM) specifies 
how browsers should create a model of an HTML 
page and how JavaScript can access and update the 
contents of a web page while it is in the browser window.

- As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. 
It consists of four main types of nodes. 

- Accessing and updating the DOM tree involves two steps: 

1- Locate the node that represents the element you want to work with. 

2- Use its text content, child elements, and attributes.

- The terms elements and element nodes are used interchangeably but when people say the DOM is working with an element, it is actually working with a node that represents that element. 

- DOM trees have four types of nodes: 

   - document nodes
   - element nodes
   -  attribute nodes
   - text nodes

- You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax.  

- Whenever a DOM query can return more than one 
node, it will always return a Nadel i st.

- From an element node, you can access and update its content using properties such as textContent and i nnerHTML or using DOM manipulation techniques. 

- An element node can contain multiple text nodes and child elements that are siblings of each other. 

- In older browsers, implementation of the DOM is 
inconsistent (and is a popular reason for using jQuery).

- Browsers offer tools for viewing the DOM tree .
-------
-----


refrences :
 
 From the Duckett JS book

Chapter 3: “Object Literals” (pp.100-105)
Chapter 5: “Document Object Model” (pp.183-242)

