# Dynamin Web Pages with JavaScript

## The Document Object

The document object represents the whole document. Like other objects that represent real-world things, the document object has:

* Properties (describe characteristics of the current web page)
* Methods (perform tasks associated with the document currently loaded in the browser)
* Events (you can respond to events, such as a user clicking or tapping on an element)

### How a Browser Sees a Web Page

1. The browser receives a page as HTML code
2. It creates a model of the page and store it in a memory
3. It shows a page on the screen using a rendering engine
4. All major broswers use a JavaScript interpreter (or scripting engine) to translate your instructions (in JavaScript) so the computer can follow

### How do computers fit in with the world around them?

* Computers create models of the world using data
* The models use objects to represent physical things
* Objects can have properties that tell use about the object
* Objects can have methods that perform tasks using the properties of that object
* Objects can have events which are triggered when a user interacts with the computer
* Programmers can write code to say "When this event occurs, run this code"
* Web browsers use HTML markup to create a model of the web page
* Each element creates its own node (a kind of object)
* To make web pages interactive, you write code that uses the browser's model of the web page

## How Do I Write a Script for a Web Page?

### How HTML, CSS & JavaScript Work Together

Aim to keep these three languages in separate files, with the HTML page linking to the CSS and JavaScript files. Each language forms a separate layer with a different purpose.

### HTML

**CONTENT LAYER**

HTML gives the page structure and adds semantics

### CSS

**PRESENTATION LAYER**

CSS enhances the HTML page with rules that state how the HTML content is presented

### JavaScript

**BEHAVIOR LAYER**

JavaScript adds interactivity to the web page

## Basic JavaScript Instructions

### Statements

A script is a series of instructions that a compuer can follow one-by-one


### Comments

A comment explains what the code does to help make the code easier for you to read and understand

### Variables

A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.

#### How to assign variables a value

The equal sign is an assignment operator. It says that you are going to assign a value to the variable. Until then, it is undefined. 

### Data Types

* Numeric Data Type
* String Data Type
* Boolean Data Type

