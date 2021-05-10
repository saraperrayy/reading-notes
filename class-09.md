# Forms and JS Events

## Chapter 7: Forms (p.144-175)

HTML borrows the concept of a form (printed document that contains spaces for you to fill in information) to refer to different elements that allow you to collect information from visitors on your site. Whenever you want to collect information from visitors you need to use a <form> element.

### Form Controls

#### Adding Text

##### Text input

* `<input>`
* example: <input> 
* **type="text"** creates a single line text input
* **name**- the value of this attribute identifies the form control and is sent along with the information they enter to the server
* **maxlength**- you can use this attribute to limit the number of characters

##### Password input

* `<input>`
* **type="password"**
* **name** indicates the name of the password input
* **maxlength** 

##### Text area (multi-line)

* `<textarea>`
* example: <textarea>

#### Making Choices

##### Radio buttons 

* when a user must select one of a number of options
* `<input>`
* **type="radio"**
* **name**
* **value** of each button in a group should be different
* **checked** attribute is used to indicate which value, if any, should be selected when the page loads

##### Checkboxes

* `<input>`
* **type="checkbox"**
* **name**
* **value**
* **checked**

##### Drop-down boxes

* `<select>` allows users to select one option from a drop down list
* **name**
* `<option>` element is used to specify the options that the user can select from
* **value**- the `<option>` element uses the value that is sent to the server along with the name of the control if this option is selected
* **selected** 

##### Multiple select box

* `<select>`
* **size**- you can turn a drop down select box into a box that shows more than one option by adding the size attribute
* **multiple**- you can allow users to select multiple options from the list by adding the multiple attribute

##### File input box

* `<input>`
* **type="file"**

##### Submit button

* `<input>`
* **type="submit"
* **name**
* **value**

##### Image button

* `<input>`
* **type="image"
* if you want to use an image for the submit button, you can give the attribute a value of image

##### Grouping form elements

* `<fieldset>` groups related form controls together
* `<legend>` comes after fieldset and contains a caption to identify the purpose of that group of form controls

## Chapter 14: Lists, Tables & Forms (pp.330-357)

* List markers can be given different appearances using the list-style-type and list-style image properties
* Table cells can have a different border and spacing in different browsers, but there are properties you can use to control them and make more consistent
* Forms are easier to use if the form controls are vertically aligned using CSS
* Forms benefit from styles that make them feel more interactive

## Chapter 6: Events (pp.243-292)

Events are the browser's way of indicating when something has happened

### Different Event Types

Any of these events can be used to trigger a function in your JavaScript code

#### UI Events

* occur when a user interacts with the browser's user interface rather than the web page
* **load**- web page has finished loading
* **unload**- web page is unloading (usually because a new page was requested)
* **error**- browser encounters a JavaScript error or an asset doesm't exist
*  **resize**- browser window has been resized
* **scroll**- user has scrolled up of down the page

#### Keyboard Events

* occur when a user interacts with the keyboard
* **input**- fires when the value of an `<input>` or `<textarea>` element changes
* **keydown**- user first presses a key
* **keyup**- user releases a key
* **keypress**- character is being inserted

#### Mouse Events

* occur when a user interacts with a mouse, trackpad or touchscreen
* **click**- user presses and releases a button over the same element
* **dblclick**- ...presses and releases button twice...
* **mousedown**- ...presses a mouse button...
* **mouseup**- ...releases a mouse button...
* **mousemove**- ...moves the mouse (not on a touchscreen)
* **mouseover**- ...moves the mouse over an element (not on a touchscreen)
* **mouseout**- ...moves the mouse off an element (not on a touch screen)

#### Load

The load event is commonly used to trigger scripts that access the content of the page

#### Focus and Blur

The HTML elements you can interact with, such as links and form elements, can gain focus. These events fire when they gain or lose focus

### W3C DOM Events

The DOM events specification is managed by the W3C (who also look after other specifications including HTML, CSS and XML)

### HTML5 Events

The HTML5 specification deltails events that browsers are expected to support that are specifically used with HTML

### BOM Events

Browser manufacturers also implement some events as part of their *Browser Object Model*. Typically, these events are not covered by W3C specifications

### Summary 

* when an event has occurred, it is often described as having **fired** or been **raised**
* events are said to **trigger** a function or script
* **binding** is the process of stating which event you are waiting to happen, and which element you are waiting for the event to happen upon
* you can use event delegation to monitor for events that happen on all of the children of an element
* the most commonly used events are the W3C DOM events, although there are others in HTML5 specification as well as browser-specific elements