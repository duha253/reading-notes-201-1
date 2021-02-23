## Reading
“The Past, Present, and Future of Local Storage for Web Applications”








### A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5

In the beginning, there was only Internet Explorer,then Microsoft invented DHTML Behaviors, and one of these behaviors was called userData then,userData allows web pages to store up to 64 KB of data per domain,In 2002, Adobe introduced a feature known as Local Shared Objects In 2007, Google launched Gears,Gears can store unlimited amounts of data per domain in SQL database tables.Despite heroic efforts to paper over the differences (in dojox.storage), they all expose radically different interfaces, have different storage limitations, and present different user experiences.




**USING HTML5 STORAGE**
HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript.


### TRACKING CHANGES TO THE HTML5 STORAGE AREA 
If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.
- LocalStorage has four methods

- localStorage.getItem(“data”)

- localStorage.setItem(“data”,data)

- localStorage.remove()

- localStorage.removeItem(“data”)


![html5](image.jpg/html5.png)

