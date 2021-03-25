# Designing Web Pages with CSS

The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element. CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented. CSS associates these style rules with HTML elements. These rules govern how the content of specific elements should be displayed. 

## Block & Inline Elements

Block level elements look like they start on a new line. Examples:

* `<b>`
* `<i>`
* `<img>`
* `<em>`
* `<span>`

## Boxes

* Width and height
* Borders (color, width, and style)
* Background colors and images
* Position in the browser window

## Text

* Typeface
* Size
* Color
* Italics, bold, uppercase, lowercase, small-caps

## Specific

* There are also specific ways in which you can style certain elements such as lists, tables, and forms

## CSS Rule

A CSS rule contains two parts: a **selector** and a **declaration**

### Selector

A selector indicated which element the rule applies to. The same rule can apply to more than onde element if you separate the element names with commas.

### Declarations

Declarations indicate how the elements referred to in the selector should be styled. Declarations are split into two parts: **property** and **value**

#### Property

Properties indicate the aspect of the element you want to change: color, font, width, height and border.

#### Values

Values specify the settings you want to use for the chosen properties. 

## External CSS

* **<link>** can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It does not need a closing tag.
* **href** specifies the path to the CSS file
* **type** specifies the type of document being linked to
* **rel** specfies the relationship between the HTML page and the file it is linked to

## Internal HTML

**<style>** elements are placed inside the <head> to apply CSS rules within an HTML page

## CSS Selectors

* Universal Selector: applies to all elements in the document. Examples: * and {}
* Type Selector: matches elements name. Example: h1, h2, h3
* Class Selector: matches an element whose class attribute has a value that matches the one specified after the period symbol. Example: . note or p.note
* ID Selector: mathes an element whose id attribute has a value that matches the one specified after the pound symbol. Example: #introduction
* Child Selector: matches an element that is a direct child of another. Example: li>a
* Descendant Selector: matches an element that is a descendant of another specified element. Example: p a 
* Adjacent Sibling Selector: matches an element that is the next sibling of another. Example: h1+p
* General Sibling Selector: Matching an element that is a sibling of another, although it does not habe to be the directly preceding element. Example: h1-p

## How CSS Rules Cascade

* **Last Rule**: if the two selectors are identical, the latter of the two will take precedence.
* **Specificity**: if one selector is more specific than the others, the more specific rule will take precedence over more general ones. 
* **Important**: you can add **!important** after any property value to indicate that it should be considered more important than other rules

## Review

* If you have two <p> elements that are siblings of a <h1> element, the general sibling selector rule applies
* h1+p targets the first <p> element after any <h1> element (but not other <p> elements)
* p a {} targets any <a> elements that sit inside a <p> element, even if there are other elements nested between them
* CSS treats each HTML element as it appears inside its own box and uses rules to indicate how that element should look
* Rules are made up of selectors and declarations
* Different types of selectors allow you to target your rules at different elements
* Declarations are made up of two parts: properties and values
* CSS rules usually appear in a separate document, although they may appear within an HTML page

## Review Questions

1. What is an empty element?
2. What does a period symbol mean?
3. What does CSS stand for?

### Review Answers

1. Empty elements do not need a closing tag
2. Full Stop
3. Cascading Style Sheet