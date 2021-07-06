# Docs for the HTML <canvas> Element & Chart.js

## Notes from the article [Easily Create Stunning Animated Charts with Chart.js](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/) written by Sara Vieira

Chart.js is a JavaScript plugin that uses HTML5's canvas element to draw the graph onto the page

1. Create a `canvas` element in HTML
2. Write a script that will retrieve the context of the canvas and add to the foot of your `body` element
3. Create data by supplying a value
4. Apply colors
5. Add options and style rules

## Notes from [Basic usage of canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)

### The `<canvas>` element

* only has 2 attributes: `width` and `height`
* when no attributes are specified, the canvas will initially be 300 px wide and 150 px high
* can be styled like any normal image using margin, border, background rules
* easy to display fallback content in the event an older browser does not support the element
* a `</canvas>` tag is required as a consequence of the way the fallback is provided

## Notes from [Drawing shapes with canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)

### The grid

* Normally, 1 unit in the grid corresponds to 1 pixel on the canvas

### Drawing rectangles

* `<canvas>` only supports two primitive shapes: rectangles and paths (lists of points connected by lines)

There are 3 functions that draw rectangles on the canvas:

1. `fillRect(x, y, width, height)`
Draws a filled rectangle.

2. `strokeRect(x, y, width, height)`
Draws a rectangular outline.

3. `clearRect(x, y, width, height)`
Clears the specified rectangular area, making it fully transparent

### Drawing paths

* `beginPath()`: Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up
* Path methods: Methods to set different paths for objects
* `closePath()`: Adds a straight line to the path, going to the start of the current sub-path
* `stroke()`: Draws the shape by stroking its outline
* `fill()`: Draws a solid shape by filling the path's content area

### Lines

* `lineTo(x, y)`: Draws a line from the current drawing position to the position specified by `x` and `y`

### Arcs

To draw arcs or circles, we use the arc() or arcTo() methods.

* `arc(x, y, radius, startAngle, endAngle, counterclockwise)`: Draws an arc which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction indicated by counterclockwise (defaulting to clockwise)
* `arcTo(x1, y1, x2, y2, radius)`: Draws an arc with the given control points and radius, connected to the previous point by a straight line

## Notes from [Applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)

### Colors

If we want to apply colors to a shape, there are two important properties we can use: `fillStyle` and `strokeStyle`

* `fillStyle = color`: Sets the style used when filling shapes
* `strokeStyle = color`: Sets the style for shapes' outlines

### Transparency

This is done by either setting the `globalAlpha` property or by assigning a semi-transparent color to the stroke and/or fill style.

* `globalAlpha = transparencyValue`: Applies the specified transparency value to all future shapes drawn on the canvas. The value must be between 0.0 (fully transparent) to 1.0 (fully opaque). This value is 1.0 (fully opaque) by default

### Line Styles

* `lineWidth = value`: Sets the width of lines drawn in the future
* `lineCap = type`: Sets the appearance of the ends of lines
* `lineJoin = type`: Sets the appearance of the "corners" where lines meet
* `miterLimit = value`: Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes
* `getLineDash()`: Returns the current line dash pattern array containing an even number of non-negative numbers
* `setLineDash(segments)`: Sets the current line dash pattern
* `lineDashOffset = value`: Specifies where to start a dash array on a line

## Notes from [Drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)

The canvas rendering context provides two methods to render text:

* `fillText(text, x, y [, maxWidth])`: Fills a given text at the given (x,y) position. Optionally with a maximum width to draw
* `strokeText(text, x, y [, maxWidth])`: Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw

### Styling text

* `font = value`: The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.
* `textAlign = value`: Text alignment setting. Possible values: `start`, `end`, `left`, `right` or `center`. The default value is `start`.
* `textBaseline = value`: Baseline alignment setting. Possible values: `top`, `hanging`, `middle`, `alphabetic`, `ideographic`, `bottom`. The default value is `alphabetic`.
* `direction = value`: Directionality. Possible values: `ltr`, `rtl`, `inherit`. The default value is `inherit`.