# Chapter 10: Error Handling & Debugging

## Execution context & Hoisting

Each time a script enters a new execution context, there are two phases of activity:

### 1. Prepare

* the new scope is created
* variables, function and arguments are created
* the value of this keyword is determined

### 2. Execute

* now it can assign values to variables
* reference functions and run their code
* execute statements

**Hoisting** allows you to:

* call the functions before they have been declared
* assign a value to a variable that has not yet been declared

## JavaScript Errors

1. **Error**- generic error
2. **SyntaxError**- syntax has not been followed
3. **ReferenceError**- tried to reference a variable that is not declared/within scope
4. **TypeError**- an unexpected data type that cannot be coerced
5. **RangeError**- numbers not in an acceptable range
6. **URIError**- encodeURI(), decodeURI(), snd similar methods used incorrectly
7. **EvalError**- eval() function used incorrectly

## Debugging Workflow

1. Look at the error message
2. Check how far the script is running
3. Use breajpoints where things are going wrong

## Debugging Tips

* **use another browser** — some errors are browser specific
* **add numbers** — write numbers to the console so you can see which items get logged
* **strip it back** — remove parts of the code and strip it down to the minimum you need
* **explaining the code** — programmers often report finding a solution to a problem while explaining the code to someone else
* **search** — Stack Overflow is a Q+A site for programmers
* **code playgrounds** — ask about a problematic code and paste the code into the post
* **validation tools** — use online tools like www.jslint.com , www.jsonlint.com , or a JQuery debugger available as a Chrome plugin
Deduction

## Common Errors

* JavaScript is case sensitive
* if you cannot access a variable's value, check if it is out of scope
* do not use reserved words or dashes in variable names
* check that your single/double quotes match
* check that you have escaped quotes in variable values
* check in HTML that values of your id attributes are unique
* every statement should end in a semicolon
* check there are no missing closing braces or parentheses
* check that there are no commas inside a bracet or parentheses
* always use parenthese to surround a condition that you are testing
* check the script is not missing a parameter when calling a function
* undefined is not the same as null
* null is for objects
* undefined is for properties, methods or variables
* using = rather than == will assign a value to a variable rather than check that the values match
* if you are checking whether values match, try a strict comparision (===)
* inside a switch statement, the values are not loosely typed
* once there is a match in a switch statement, all expressions will be executed until the next break or return statement
* the replace() method only replaces the first match
* to replace all occurences, use the global flag

## Summary 

* If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code
* **Debugging** is the process of finding errors & involves deduction
* The console helps narrow down the area in which the error is located
* Java Script has 7 different types of error
* If you know you may get an error, you can handle it gracefully using the **try, catch, finally** statements
