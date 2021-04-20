# HTML Links, CSS Layout, JS Functions

## Chapter 4: Links (pp.74-93)

### Writing Links

Links are created using the `<a>` element. The `<a>` element uses the href attribute to indicate the page you are linking to. Example: `<a href+http://www.imdb.com">IMDB</a>`

### Relative Links

If you are linking to your page within your own site, it is best to use relative links rather than qualified URLs.

* **Same folder**: to link a file in the same folder, just use the file name
* **Child folder**: use the name of the child folder, followed by a forward slash, then the file name
* **Grandchild folder**: use the name of the child folder, followed by a forward slash, then the name of the grandchild folder, followed by another forward slash, then the file name
* **Parent folder**: use the `../` to indicate the folder above the current one, then follow it with the file name
* **Grandparent folder**: repeat the `../` to indicate that you want to go up two folders, then follow it with the file name

## Chapter 15: Layout (pp.358-404) pp.358-364

* <div> elements are often used as containing elements to group together rections of a page
* browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning
* the float property moves content to the left or right of the page and can be used to create multi-column layouts
* Floated items require a defined width
* Pages can be fixed width or liquid (stretchy) layouts
* Designers keep pages within 960-10000 pixels wide, and indicate what the site is about within the top 600 pixels
* Grids help create professional and flexible designs
* CSS Frameworks provide rules for common tasks
* You can include multipple CSS files in one page

### Vocabulary

* **Block level elements**: start on a new line
* **inline elements**: flow in between surrounding text
* **Containing elements**: if one block level element sits inside another block level element, the the outer box is known as the containing or **parent element**
* **Positioning schemes**: normal flow, relative positioning and absolute positioning allow you to control the layout of the page
* **Normal flow**: every block level element appears on a new line causing each item to appear lower down the page than the previous one
* **Relative positioning**: moves and element from the position it would be in normal flow, shifting it to the top, right, bottom or left of where it would have been placed
* **Absolutely positioning**: positions the element in relation to its containing element. It is taken out of normal flow, meaning it does not affect the position of any surrounding elements
* **Fixed positioning**: is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element
* **Floating elements**: allow you to take the element out of normal flow and position it to the far left or right of a containing box
* **z-index**: allow you to control which box appears on top

## Chapter 3 (first part): Functions (pp.86-99 ONLY)

* Functions allow you to group a set of related statements together that represent a single task
* Functions can take parameters and may return a rule
* Parameters outline the information required for a function to do its job