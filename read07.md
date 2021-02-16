# What's a Table?
A table represents information in a grid format. 

### -Basic Table Structure

<table>  element tag to create table.
<tr> start the table using it.(table row).
<td> to write the table data.
<th> table heading to represent the heading for either a column or a row.

### how to create a table in html 

- put < table> tag to create table.

- < tr > tag for start each row. its created with the < tr> element.

- inside the < tr > tag put < td > tag for each column in row.

- you can also put < th > head after table tag to enter header for table.

- You can make cells of a table span more than one row or column using the rowspan and colspan attributes.


**Tables Long , for the long of the  table we can write the table inside these elements** 

- <thead> the heading of the table will written inside it .

- <tfoot> the footer of the table will written inside it. 

- <tbody>  the body of the table will written inside it.


 ### So the table

- The <table element is used to add tables to a web page.

 - A table is drawn out row by row. Each row is created with the <tr> element.

- Inside each row there are a number of cells represented by the <td> element (or <th> if it is a header).

- You can make cells of a table span more than one row or column using the rowspan and colspan attributes.

- For long tables you can split the table into a <thead>,<tbody>, and <tfoot>.






# Objects

### What is Objects ?

**_Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names_**.

**_global object A global object is an object that always exists in the global scope_**.
_In JavaScript, there's always a global object defined. In a web browser, when scripts create global variables defined with the var keyword, they're created as members of the global object. (In Node.js this is not the case.) The global object's interface depends on the execution context in which the script is running. For example,_

**In a web browser, any code which the script doesn't specifically start up as a background task has a Window as its global object. This is the vast majority of JavaScript code on the Web**.

Code running in a Worker has a WorkerGlobalScope object as its global object.
Scripts running under Node.js have an object called global as their global object.


### Functions, Methods, and Objects 

*Functions allow you to group a set of related statements together that represent a single task.

*Functions can take parameters (informatiorJ required to do their job) and may return a value.

*An object is a series of variables and functions that represent something from the world around you.

*In an object, variables are known as properties of the object; functions are known as methods of the object.

*Web browsers implement objects that represent both the browser window and the document loaded into the browser window.

*JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.

*Arrays and objects can be used to create complex data sets (and both can contain the other). 







