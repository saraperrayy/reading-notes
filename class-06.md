# Problem Domain, Objects, and the DOM

## Object Literals (pp.100-105)

Objects group together a set of variables and functions to create a model of something you would recognize from the real world. In an object, variables and functions take on a new name.

In an object:

* variables become properties
* functions become methods
* a name becomes a key
* the value of a property can be a string, number, Boolean, array or even another project
* the value of a method is always a function
* you can access the properties or methods using dot notation or square brackets

## Document Object Model (pp.183-242)

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

* DOM Tree: the DOM uses this to specify the way in which the browser should structure the model (a model of the web page)
* DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text modes
* You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax
* Whenever a DOM query can return more than one node, it will always return a NodeList
* From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques
* An element node can contain multiple text nodes and child elements that are siblings of each other
