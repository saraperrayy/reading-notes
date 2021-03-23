# Structure Web Pages with HTML

Structure is important in helping the reader understand the message that you are trying to convey. HTML structure is similar to the structure of a Word document, insurance for or even a newspaper. A hierachy of information is reflected in the structure of these documents with the use of headings, subheadings and paragraphs.

## What is HTML

HTML stands for HyperText Markup Language. The "HyperText" part of "HyperText Markup Language" refers to the fact that HTML allows you to create links that allow visitors to move from one page to another. The following information was gathered from notes on [Chapter 1](https://wtf.tw/ref/duckett.pdf) of HTML and CSS by Jon Duckett.

A markup language allows you to annotate text, and these annotations provide additional meaning to the contents of the document. The tags we add are the markup.

## HTML Describes the Structure of Pages

HTML uses different elements to describe the structures of pages. Each element has an opening and a closing tag. The tags act like containers and tell you something about the information that lies between their opening and closing tags. An opening tag is an element placed between a left-angle bracket and a right-angle bracket. A closing tag is nearly identical, however it includes a forward slash immediately following the first bracket.

`<title>` The contents of the title element are either shown in the top of the browser, above where you usually type the URL, or on the tab for that page.

`<html>` This is an opening HTML tag. The `<html>` tag indicates that anything between it and the closing HTML tag is an HTML code. The opening HTML tag is placed at the begining of your web document, whereas the closing HTML is placed at the end.

`<head>` The head tag is placed before the body element. This contains information about the page, rather than information shown within the main part of the browser window.

`<body>` The body tag indicates that anything between it and the closing body tag should be shown inside the main browser window.

`<h1>This is the Main Heading</h1>` A heading introduces a new topic and creates a sense of structure within your document. The heading is formatted differently than the sub-headings and paragraphs to visually demonstrate a hierachy of information. Words between `<h1>` and `</h1>` are a main heading.

`<p>This is a paragraph of the main body text. This text might be an introduction to the rest of the page. If the page is long, it might be split up into several subheadings.<p>` A paragraph of text appears between an opening paragraph tag `<p>` and a closing paragraph tag `</p>`.

`<h2>This is a Sub-Heading</h2>` A subheading follows the same structure as its predecessors by starting with an opening tag and ending with a closing tag. The number associated with the sub heading tag reflects the hierachy of the document.

`<p>This is another paragraph of body text. Many long articles have sub-headings to help you follow the structure of what is being written.</p>`

`<h2>Another Sub-Heading</h2>`

`<p>This is a body of text that follows the sub-heading before concluding the body text.</p>`

`</body>` This is a closing body tag. This indicates the end of what should appear in the main browser window.

`</html>` This is the closing HTML tag. This indicates the end of the HTML code.

### HTML Attributes

Attributes tell us more about an element. Attributes provide additionsl innformation about the content of an element and appear on the opening tag. Attributes are made up of two parts: a **name** and a **value**, spearated by an **equal sign**.

Here is an attribute called *lang* is used to indicate the language used in this element. The value of this attribute on this page specifies it is in US English. Most attributes can only be used on certain elements, however a few, like *lang* can appear on any element.

`<p lang="en-us"> Paragraph in english</p>`

#### Attribute Name

The attribute **name** indicates the extra information about the element's content. *It should be written in lowercase.*

Attribute Name: lang

#### Attribute Value

The **value** is the information or setting for the attribute. *It should be placed inside double quotes.* Different attributes can have different values. Most attributes are either predefined or follow a stipulated format. The value of the *lang* is an abbreviated way of specifying which language is used inside the element that all broswers understand.

Attribute Value: "en-us"

### Creating a Web Page on a Mac

1. Go to Applications
2. Open Text Edit or a Text Editor like VS Code
3. Type your code
4. Go to the **File** menu and select **Save As**
5. Select the **Use .html** button
6. In your browser, go to the **File** menu and select **Open**

### Review

* HTML pages are text documents
* MTNL uses tags to give the info they surround a special meaning
* Tags can be referred to as elements
* Tags usually come in pairs
* Opening tags carry attributes, which tell us more about the content of that element
* Attributes require a name and value

## HTML5

HTML5 introduces a new set of elements that allows you to divide the various parts of a page. The names of these elements indicate the kind of content you will find in them. The point of creating these new elements is so that web page authors can use them to describe the structure of the page. This section outlines the information provided by [Chapter 17](https://wtf.tw/ref/duckett.pdf) of HTML and CSS by Jon Duckett.

### Headers and Footers

Headers and footers can be used for:
* The main header/footer at the top/bottom of every site page
* A header/footer for an idividual article or section

### Navigation

The `<nav>` element is used to contain the major navigational blocks on the site.

### Articles

The `<article>` element acts as a container for any section of a page that could stand alone and potentially be syndicated. If a page contains several articles, then each article would live inside its own `<article>` element. Article elements can even be nested inside each other.

### Asides

The aside element has two purposes:

* When the <aside> element is used inside an <article> element, it should contain information that is related to the article, but not essential to its overall meaning.
* When the <aside> element is used outside an <article> element, it acts as a container for content that is related to the entire page. Ex: links to other areas of the site

### Sections

* The <section> element groups related content together, and typically each section would have its own heading
* It can contain several distinct <article> elements that have a common theme or purpose
* If you have a long article, the <section> element can be used to split the article int separate sections
* Should not be used as a wrapper for the entire page unless the page contains only one piece of content — use the <div> element

### Heading Groups

The purpose of the <hgroup> element is to group together a set of one or more <h1> elements so they are treated as one single heading.

### Figures

The <figure> element can be used to contain any content that is referenced from the main flow of an article. The <figure> element should also contain a <figcaption> which provides a text description for the content. Examples:

* Images
* Videos
* Graphs
* Diagrams
* Code samples
* Text that supports the main body of an article

### Sectioning Elements

When there is no suitable element to group a set of elements, the <div> element will still be used.

### Review

* HTML5 elements indicate the purpose of the different parts of a web page to describe its structure
* HTML5 elements provide clearer code
* Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements
* Extra JavaScript is needed for HTML5 to work in Internet Explorer 8

## Extra Markup

This section highlights the key information from [Chapter 8](https://wtf.tw/ref/duckett.pdf) of HTML and CSS by Jon Duckett.

* DOCTYPES tell browsers which version of HTML you are using
* You can add comments to your code between the `<!-- and -->` markers
* The id and class attributes allow you to identify particular elements
* The <div> and <span> elements allow you to group block-level and inline elements together
* <iframes> cut windows into your webpages through which other pages can be displayed
* The <meta> tag alllows you to supply all kinds of information about your web page
* Escape characters are used to include special characters in your pages such as <, >, and ©

## Process and Design

This section outlines details from [Chapter 18](https://wtf.tw/ref/duckett.pdf) of HTML and CSS by Jon Duckett about basic design concepts and the design process involved in a website.

* How to approack build a site
* Understanding your audience and their needs
* How to present information visitors want to see

### Who is the site for?

Every site should be designed for a target audience. You should assess the demographics of your target audience and create fictional characters to create personality applicable to the subject. 

### Why are people visiting your site?

Most visitor have a specific reason for landing on your site. Identify key motivators and specific goals. 

### What are your visitors trying to achieve?

Create a list of reasons that visitors may be on your site and assign the reasons to your fictional characters. 

### What information do visitors need?

Supply visitors with key supporting information that they need to achieve their goal.

### How often do people visit your site?

Some websites benefits from frequently updated content, whereas others do not need to be updated as often.

### Sitemaps

Sitemaps organize your information into sections or pages. The aim is to create a diagram of the pages to structure the site.

### Wireframes

* A simple sketch of key information that needs to go on each page
* Do not include color scheme, special fonts or backgrounds
* This plain layout is helpful to showcase the functionality of the site to your client

### Visual Hierachy

This refers to the order your eyes perceive what they see.

* Size
* Color
* Design

### Grouping

Grouping related pieces of information together can make design easier to comprehend. Here are examples of grouping:

1. Proximity
2. Closure
3. Continuance
4. White Space
5. Color
6. Borders

### Design Navigation

Site navigation help people find where they want to go and helps them understand what your site is about and how it is organized. Good navigation follows these prinicples:

1. Concise
2. Clear
3. Selective
4. Context
5. Interactive
6. Consistent

