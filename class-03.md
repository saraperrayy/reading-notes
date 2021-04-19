# HTML Lists, Control Flow with JS, and the CSS Box Model

## Chapter 3: Lists (pp.62-73)

### Lists

* Ordered Lists: `<ol>`
* Unordered Lists: `<ul>`
* Definition Lists: usually consists of a series of terms and their definition. `<dl>` creates the list, `<dt>` contains the term being defined, and `<dd>` contains the definition
* Nested list: you can put a second `<li>` inside another to create a sub-list

## Chapter 13: Boxes (pp.300-329)

### Boxes

* CSS treats each HTML element as if it has its own box
* You can use CSS to control the dimensions of a box
* You can control the borders, margin and padding for each box with CSS
* It is possible to hide elements using the display and visibility properties
* Block level boxes can be made into inline boxes, and inline boxes can be made into block level boxes
* Legibility can be improved by controlling the width of boxes containing text and the leading
* CSS3 introduced the ability to create image borders and rounded borders

## Review Chapter 2: Basic JavaScript Instructions (pp.70-73)

### Array

An array is a special type of variable. It doesn't just store one value; it stores a list of values. You should consider using an array whenever you are working with a list or a set of values that are related to each other.

### Array Literal

The preferred method of creating an array. The values in the array do not need to be the same data type, so you can store a string, number and a Boolean all in the same array.The values assigned to the array inside a pair of square brackets, and each value is separated by a comma.

### Array Constructor

This uses the new keyword followed by `Array();`The values are then specified in parentheses not square brackets, and each value is separated by a comma and placed in different lines. You can also use a method called `item()` to retrieve data from the array. 

### Numbering Items in an Array

Each item in an array is automatically giveb a number called an index. This can be used to access specific items in the array

## Chapter 4: Decisions and Loops (pp.162-182)

### Statements

* Conditional statements allow your code to make decisions about to do next
* Comparision operators are used to compare two operands
* Logical operators allow you to combine more than one set of comparison operators
* Data types can be coerced from one type to another
* all values evaluate to either truthy or falsy
* There are three types of loop: for, while, and do...while. Each repeats a set of statements

### If...Else Statements

The **if...else** statement checks a condition. If it resolves **true**, the first code block is executed. If the condition resolves **false**, the second code block is run instead.

### Switch Statements

A switch statement starts with a variable called the **switch value**. Each case indicates a possible value for this variable and the code that should run if the variable matches that value. 

* You have a **default** option that is run if none of the cases match
* If a match is found, that code is run; then the **break** statement stops the rest of the switch statement running.