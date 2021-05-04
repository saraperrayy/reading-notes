# Object-Oriented Programming, HTML Tables

## Chapter 6: Tables (pp.126-145)

* <table>: table element is used to add tables to a web page
* <tr>: table row. A table is drawn out row by row
* <td>: table data
* <th>: table heading
* you can make cells of a table span more than one row or column using the rowspan colspan attributes
* for long tables, you can split the table into a <thead>, <tbody>, and <tfoot>

## Chapter 3: Functions, Methods, and Objects (pp.106-144)

### The Document Object

* document.title property: title of current document
* document.lastModified property: date on which document was last modified
* document.url property: returns a string containing URL of current document
* document.domain property: returns domain of current document
* document.write() method: writes text to document
* document.getElementById() method: returns element, if there is an element with the value of the id attribute that matches
* document.querySelectorAll() method: returns list of elements that match CSS selector, which is specified as a parameter
* document.createElement() method: creates a new element
* document.createTextNode() method: creates new text node

* Functions allow you to group a set of related statements together that represent a single tash
* Functions can take parameters and may return a value
* An object is a series of variables and functions that represent something from the world around you
* In an object, variables are known as properties of the object, functions are known as methods of the object
* **isNan()**: method that checks if the value is not a number
* **toFixed()**: method that rounds to a specific number of decimal places and returns a string
* **toPrecision()**: method that rounds to total number of places and returns a string
* **toExponential()**: method that returns a string representing the number in exponential notation
* **integer**: a whole number (not a fraction)
* **real number**: number that can contain a fractional part
* **floating point number**: a real number that uses decimals to represent a fraction
* **scientific notation**: a way of writing numbers that are too big or too small to be be conveniently written in decimal form
* Web browsers implement objects that represent both the browser window and the document loaded into browser window
* JavaScript also has several built-in objects duch as **string, number, math and date**
* The **Date()** object constructor tells the JavaScript interpreter that this variable is a date, and this in return allows you to use the Date object's methods to set and retrieve dates and times from this Date object
* Arrays and objects can be used to create complex data sets (and both can contain the other)

### Global Objects: String Object

* length property: returns number of characters in the string in most cases
* toUpperCase() method: changes strings to uppercase characters
* toLowerCase() method: changes strings to lowercase characters
* CharAt() method: takes an index number as a parameter, and returns the character found at that position
* indexOf() method: returns index number of the first time a character or set of characters is found within the string
* lastIndexOf() method: returns index number of the last time a character or set of characters is found within the string
* substring() method: returns characters found between two index numbers where the character for the index number is included and the character for the last index number is not included
* split() method: when a character is specified, it splits each time it is found, then stores each individual part in an array
* trim() method: removes whitespace from start and end of string
* replace() method: takes one value that should be found, and another to replace it (by default, it only replaces the first match it finds) 
