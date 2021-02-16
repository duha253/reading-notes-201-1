
# Why Forms?
In addition to enabling users to search, forms also allow users to perform other functions
online. 


## The <form> Element.

HTML Forms are required, when you want to collect some data from the site visitor. For example, during user registration you would like to collect information such as name, email address, credit card, etc.

A form will take input from the site visitor and then will post it to a back-end application such as CGI, ASP Script or PHP script etc. The back-end application will perform required processing on the passed data based on defined business logic inside the application.
There are various form elements available like text fields, textarea fields, drop-down menus, radio buttons, checkboxes, etc.




The HTML <form> element can contain one or more of the following 

### form elements:
<input>
<label>
<select>
<textarea>
<button>
<fieldset>
<legend>
<datalist>
<output>
<option>
<optgroup>



### HTML Form Controls.

There are different types of form controls that you can use to collect data using HTML form 

- Text Input Controls.

- Checkboxes Controls.

- Radio Box Controls.

- Select Box Controls.

- File Select boxes.

- Hidden Controls.

- Clickable Buttons.

- Submit and Reset Button.


#### Text Input Controls
There are three types of text input used on forms 
1. Single-line text input controls − This control is used for items that require only one line of user input, such as search boxes or names. They are created using HTML <input> tag.
2. Password input controls − This is also a single-line text input but it masks the character as soon as a user enters it. They are also created using HTMl <input> tag.

3. Multi-line text input controls − This is used when the user is required to give details that may be longer than a single sentence. Multi-line input controls are created using HTML <textarea> tag.

## Summary
### _FORMS_
-  Whenever you want to collect information from visitors you will need a form, which lives inside a <form> element.

- from a form is sent in name/value pairs.

-  Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.

- HTML5 introduces new form elements which make it easier for visitors to fill in forms.






# LISTS, TABLES AND FORMS.

⦁	Specifying bullet point styles

⦁	Adding borders and backgrounds to tables.

⦁	Changing the appearance of form elements.

There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms.


## BULLET POINT STYLES
list-style-type
The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker).
It can be used on rules that apply to the <ol>, <ul>, and <li> elements.

i.	List markers can be given different appearances using the list-style-type and list-style image properties.
ii.	Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.
iii.	Forms are easier to use if the form controls are vertically aligned using CSS.
iv.	 Forms benefit from styles that make them feel more interactive.






# Event.

## What is an Event ?
JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page.
When the page loads, it is called an event. When the user clicks a button, that click too is an event. Other examples include events like pressing any key, closing a window, resizing a window, etc.
Events are a part of the Document Object Model (DOM) Level 3 and every HTML element contains a set of events which can trigger JavaScript Code.



A series of fortunate events
As mentioned above, events are actions or occurrences that happen in the system you are programming ...the system produces (or "fires") a signal of some kind when an event occurs, and provides a mechanism by which an action can be automatically taken (that is, some code running) when the event occurs. For example, in an airport, when the runway is clear for take off, a signal is communicated to the pilot. As a result, the plane can safely takeoff.


**_Each available event has an event handler, which is a block of code (usually a JavaScript function that you as a programmer create) that runs when the event fires. When such a block of code is defined to run in response to an event, we say we are registering an event handler. Note: Event handlers are sometimes called event listeners — they are pretty much interchangeable for our purposes, although strictly speaking, they work together. The listener listens out for the event happening, and the handler is the code that is run in response to it happening_**.


**_Event handler properties_**

⦁	btn.onfocus  and  btn.onblur .... The color changes when the button is focused and unfocused; try pressing the tab to focus on the button and press the tab again to focus away from the button.

⦁	btn.ondblclick .... The color changes only when the button is double-clicked.

⦁	window.onkeypress, window.onkeydown, window.onkeyup .....The color changes when a key is pressed on the keyboard. The keypress event refers to a general press (button down and then up), while keydown and keyup refer to just the key down and key up parts of the keystroke.

⦁	btn.onmouseover and btn.onmouseout ... The color changes when the mouse pointer hovers over the button, or when the pointer moves off the button, respectively.


### Event delegation
Bubbling also allows us to take advantage of event delegation — this concept relies on the fact that if you want some code to run when you select any one of a large number of child elements, you can set the event listener on their parent and have events that happen on them bubble up to their parent rather than having to set the event listener on every child individually. Remember, bubbling involves checking the element the event is fired on for an event handler first, then moving up to the element's parent, etc.

A good example is a series of list items  if you want each one to pop up a message when selected, you can set the click event listener on the parent <ul>, and events will bubble from the list items to the <ul>.


