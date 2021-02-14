WHAT IS AN OBJECT?

Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.

- property. Properties tell us about the object, such as the name of a hotel or the number of rooms it has. Each individual hotel might have a different name and a different number of rooms. 
- a method. Methods represent tasks that are associated with the object. For example, you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms. 

In JavaScript:
• Variables have a name and you can assign them a value of a string, number, or Boolean.
• Arrays have a name and a group of values. (Each item in an array is a name/value pair because it has an index number and a value.)
• Named functions have a name and value that is a set of statements to run if the function is called.
• Objects consist of a set of name/value pairs (but the names are referred to as keys). 


Document Object Model:
The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. 


SELECTING AN ELEMENT FROM A NODELIST
 There are two ways to select an element from a Nodelist:

- The item() method  THE ;tern{) METHOD Nodelists have a method called item() which will return an individual node from the Node list.
and array syntax.
Both require the index number of the element you want. 


LOOPING THROUGH A NODELIST
It involves finding out how many items are in the Nodelist, and then setting a counter to loop through them, one-by-one. 


TRAVERSING THE DOM 
When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM.

1. parentNode
This property finds the element node for the containing (or parent) element in the HTML. 
2. previousSibling nextSibling These properties find the previous or next sibling of a node if there are siblings.

3.  f i rstChil d ,lastChild
These properties find the first or last child of the current element.
-WHITESPACE NODES:Traversing the DOM can be difficult because some browsers add a text node whenever they come across whitespace between elements


** ACCESS & UPDATE TEXT &
MARKUP WITH INNERHTML ; Using the i nnerHTML property, you can access and amend the contents of an element, including any child elements.

** ADDING ELEMENTS USING DOM MANIPULATION 
 CREATE THE ELEMENT createEl ement () You start by creating a new element node using the createElement() method. This element node is stored in a variable.


EXAMPLE
DOCUMENT OBJECT MODEL
This example brings together a selection of the techniques you have seen throughout the chapter to update the contents of the list.
It has three main aims:
1: Add a new item to the start and end of the list Adding an item to the start of a list requires the use of a different method than adding an element to the end of the list.
2: Set a cl ass attribute on all items This involves looping through each of the <l i >elements and updating the value of the c 1 ass attribute to coo 1.
3: Add the number of list items to the heading This involves four steps: 1. Reading the content of the heading
2. Counting the number of <:l i >elements in the page 
3. Adding the number of items to the content of the heading
4 . Updating the heading with this new content DOCUMEN



**summary

- The browser represents the page using a DOM tree.
-DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.

-You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax.

-Whenever a DOM query can return more than one node, it will always return a Nadel i st.

-From an element node, you can access and update its content using properties such as textContent and i nnerHTML or using DOM manipulation techniques.

-An element node can contain multiple text nodes and child elements that are siblings of each other.

-In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).

-Browsers offer tools for viewing the DOM tree . 

