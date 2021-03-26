# Programming with JavaScript

intro pg 1-24 

## Goal

* Understand basic programming concepts
* Learning the language
* Becoming familiar with how it is applied

## How JavaScript Makes Web Pages More Interactive

1. Access content

* Select the text inside all of the <h1> elements on a page
* Select any elements that have a class attribute with a value of note
* Find out what was entered into a text input whose id attribute has a value of email

2. Modify Content

* Add a paragraph of text after the first <h1> element
* Change the value of class attributes to trigger new CSS rules for those elements
* Change the size or position of an <img> element

3. Program Rules

You can specify a set of steps for the browser to follow, which allows it to access or change the content of a page. 

* A gallergy script could check which image a user clicked on and display a larger version of that image
* A mortgage calculator could collect values from a form, perform a calculation and display repayments
* An animation could check the dimensions of the browser window and move an image to the bottom of the viewable area (or viewport)

4. React to Events

You can specify that a script should run when a specific event has occurred. Example:

* A button is pressed
* A link is clicked
* A cursor hovers over an element
* Information is added to a form
* An interval of time has passed
* A web page has finished loading

## Slideshows

Slideshows can display a number of different images within the same space on a given page. They allow more content to be displayed within a limited amount of space.

## Forms

JavaScript lets you alert the user if mistakes have been made. It can also perform sophisticated calculations based on any data entered and reveal the result to the user.

## Reload Part of a Page

If you only need to refresh a small portion of the page, reloading onlu a section of the page can make a site feel like it is faster to load and more like an application.

## Filtering Data

You can help users find info by providing filters

## What is a Script and How Do We Create One?

* A script is a series of instructions that a computer can follow to achieve a goal
* Scripts are made up of instructions that a computer can follow step-by-step
* A broswer may use different parts of the script dependind on how the user interacts with the web page
* Scripts can run different sections of the code in response to the situation around them

### Writing a Script

To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it. 

1. Define the goal
2. Design the concept

* split your goal out into a series of tasks using a flowchart
* write down individual steps that the computer needs to perform in order to complete each individual task

3. Code each step

## Rules for naming variables

Here are six rules you must **always** follow when giving a variable a name. 

1. The name must begin with a letter, dollar sign, or and underscore. It must **not** start with a number.
2. The name can contain letter, numbers, dollar sign, or and underscore. You must **not** use a dash or a period in a variable name.
3. You **cannot** use keywords or reserved words (see vocabulary section for more information)
4. All variables are case sensitive
5. Use a name that describes the kind of info that the variable stores
6. If your variable name is made up of more than one word, use a capital letter for the first letter of every work **after** the first word.

## Arrays

An array is a special type of variable — it doesn't just store one value; it stores a list of values.

You should consider using an array whenever you are working with a **list** or a set of values that are **related** to each other.

### Creating an Array

Use the *var* keyword followed by the name of the array

The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma

Example:

`var colors;
colors + ['white', 'black', custom'];`

### Values in an Array

Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero, not one.

#### Numbering Items in an Array

Each item in an array is automatically given a number called an index

#### Accessing Items in an Array

To retrieve the third item on the list, the array name is specified along with the index number in square brackets. Example: 

`var itemThree;
itemThree = colors[2];`

Each array has a property called length, which holds the number of items in the array

## Operators

Expressions rely on things called operators; they allow programmers to create a single value from one or more values

1. Assignment operators
2. Arithmetic operators
3. String operators
4. Comparision operators
5. Logical operators

## What is a Function

Functions let you group a series of statements together to perform a specific task. If differrent parts of a script repeat the same task, you can reuse the function, rather than repeating the same set of statements. 

* statements in a function are not always executed when a page loads, so functions also offer a way to store the steps needed to achieve a task
* when you ask a function to perform its task, it is know as **calling** the function
* pieces of information passed to a function are known as **parameters**
* when you write a function & you expect it to provide you with an answer, the response is known as a **return value**
* you can also have anonymous functions that are not called on, but however executed as soon as the interpreter comes across them

### Declaring a Function

To create a function, give it a name & then write the statements needed to achieve its task inside the curly brackets. This is known as a function declaration.

### Calling a Function

Having declared the function, you can then execute all of the statements between its curly brackets with just one line of code.

### Declaring Functions That Need Info

Sometimes a function needs specific information to perform its task. In such cases, when you declare the function, you give it perameters. Inside the function, the parameters act like variables. 

### Calling Functions That Need Info

When you call a function that has parameters, you specify the values it should use in the parentheses that follow its name. The values are called **arguments**, and they can be provided as values or variables.

### Getting a Single Value Out of a Function

Some functions return information to the code that called them. For example, when they perform a calculation, they return the result.

## Vocabulary 

**Keywords** are special words that tell the interpreter to do something

**Reserved** words are ones that may be used in a future version of JavaScript

**Expressions** evaluate into (results in) a single value

**Operators** allow programmers to create a single value from one or more values

**Identifier** the function name followed by parentheses

**Statements** sit inside the curly brackets in a code block

## Review Questions

1. What is a viewport?
2. What is an array literal?
3. What is an array constructor?
4. What number do index values start at?
5. What are the two types of expressions?
6. What is a function declaratiom?

## Review Answers

1. A viewable area
2. The preferred method for creating an array: values are assigned to the array inside a pair of square brackets, and each value is separated by a comma
3. The values are specified in parenthese (not square brackets) and each value is separated by a comma
4. 0
5. Expressions that just assign value to a variable and expressions that use two or more values to return a single value
6. Giving a function a name and writing the statement needed to achieve its tasks inside the curly brackets


