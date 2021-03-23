# Structure Web Pages with HTML

Structure is important in helping the reader understand the message that you are trying to convey. HTML structure is similar to the structure of a Word document, insurance for or even a newspaper. A hierachy of information is reflected in the structure of these documents with the use of headings, subheadings and paragraphs. The following information was gathered from notes on [Chapter 1](https://wtf.tw/ref/duckett.pdf) of HTML and CSS by Jon Duckett.

## What is HTML

HTML stands for HyperText Markup Language. The "HyperText" part of "HyperText Markup Language" refers to the fact that HTML allows you to create links that allow visitors to move from one page to another.

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

## HTML Attributes

Attributes tell us more about an element. Attributes provide additionsl innformation about the content of an element and appear on the opening tag. Attributes are made up of two parts: a **name** and a **value**, spearated by an **equal sign**.

Here is an attribute called *lang* is used to indicate the language used in this element. The value of this attribute on this page specifies it is in US English. Most attributes can only be used on certain elements, however a few, like *lang* can appear on any element.

`<p lang="en-us"> Paragraph in english</p>`

### Attribute Name

The attribute **name** indicates the extra information about the element's content. *It should be written in lowercase.*

Attribute Name: lang

### Attribute Value

The **value** is the information or setting for the attribute. *It should be placed inside double quotes.* Different attributes can have different values. Most attributes are either predefined or follow a stipulated format. The value of the *lang* is an abbreviated way of specifying which language is used inside the element that all broswers understand.

Attribute Value: "en-us"

## Creating a Web Page on a Mac

1. Go to Applications
2. Open Text Edit or a Text Editor like VS Code
3. Type your code
4. Go to the **File** menu and select **Save As**
5. Select the **Use .html** button
6. In your browser, go to the **File** menu and select **Open**

## Review

* HTML pages are text documents
* MTNL uses tags to give the info they surround a special meaning
* Tags can be referred to as elements
* Tags usually come in pairs
* Opening tags carry attributes, which tell us more about the content of that element
* Attributes require a name and value
