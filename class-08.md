# Ch. 15: CSS Layout

CSS treats each HTML element as if it is in its own box. This box will either be a block-level or inline box. If one block-level element sits inside another block-level element, then the outer box is known as the containing or parent element.

* Block-level elements: start on a new line (Ex: <h1>, <p>, <ul>, <li>)
* Inline elements: flow in between surrounding text (Ex: `<img>, <b>, <i>`)

## Pages can be fixed width or liquid (stretchy) layouts

### Fixed Width Layout

Fixed width layout designs do not change size as the user increases or decreates the size of their browser

#### Advantages

* pixel values are accurate at controlling size and positioning of elements
* the designer has more control over the appearance and position of items on the page than with liquid layouts
* you can control the lengths of lines of text regardless of the size of the user's window
* the size of an image will always remain the same relative to the rest of the page

#### Disadvantages

* you can end up with big gaps around the edge of a page
* the page can look smaller and text can be hard to reaf of the screen is a higher resolution than the designers screen
* text might not fit into the allotted spaces if a user increases font sizes
* the page will often take up more vertical space than a liquid layout with the same content

### Liquid Layouts

Liquid layout designs stretch and contrast as the user increases or decreases the size of their browser window. They temd to use percentages. 

#### Advantages

* pages expand to fill the entire browser window so there are no spaces around the page on a large screen
* pages can contract to fit small windows without the user having to scroll to the side
* the design is tolerant of users setting font sizes larger than the designer's intented font size

#### Disadvantages

* if the width of sections are not controlled, the page can look different than intended, with unexpected gaps around certain elements or items squashed together
* lines of text can become very long if the window is is wide
* narrow windows mat cause words to be squashed resulting in few words on each line
* if a fixed width item, like an image, is inside a box too small to hold it, the image can overflow the text

## Adding Multiple Stylesheets

You can include multiple CSS files in one page. Some web page authors split up their CSS style rules into separate style sheets. They might use one style sheet to control the layout and another to control fonts, colors and so on. Some create separate stylesheets to control typography, layout, forms, tables and different styles for each sub-section of a site.

### Two ways to add multiple style sheets to a page

1. Link HTML to one stylesheet and use the @import rules to import other styles (use before other rules)
2. Use a separate <link> element to add a second stylesheet in the HTML

## Key Concepts

* <div> elements are often used as containing elements to group together sections of a page
* Browsers display pages in normal flow unless you specify relative, absolute or fixed positioning
* The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Float items require a defined width)
* Keep pages within 960-1000 pixels wide
* Indicate what the site is about within the top 600 pixels
* Grids create professional and flexible designs
* CSS Frameworks provide rules for commin tasks