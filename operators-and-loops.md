# Operators and Loops

## Comparision Operators

You can evaluate a situation by comparing one value in the script to what you expect it might be. The result will be a boolean. 

* Boolean: **true** or **false**
* `==`: *is equal to*, compares two values to see if they are the same
* `!=`: *is not equal*, compares two values to see if they are **not** the same
* `===`: *strict equal*, compares two values to check that both the data type and the value are the same
* `!==`: *strict not equal*, compares two values to check that both the data type and value are **not** the same
* `>`: *greater than*, checks if the number on the left is greater than the number on the right
* `<`: *less that*, checks if the number on the left is less than the number on the right
* `>=`: *greater than or equal to*, checks if the number on the left is greater than or equal to the one on the right
* `<=`: *less than or equal to*, checks if the number on the left is less than or equal to the one on the right
* `&&`: *logical and*, tests more than one condition
* `!`: *logical not*, takes a single Boolean value and inverts it/reverses the state of an expression
* `||`: *logical or*, tests atleast one condition

## Loops

Loops check a condition. If it returns true, a code block will run. Then the condition will be checked again, & if it still returns true, the code block will run again. It will repeat until the condition returns false.

* For loop: if you need to run code a specific number of times
* While loop: if you do not know how many times the code should be run
* Do while loop: it will always run the statements inside the curly braces at once, *even if the condition equals false*

## Using While Loops

* `+=` operator: used to add content to the message variable. Works as shorthand for writing msg = msg + 'new msg'