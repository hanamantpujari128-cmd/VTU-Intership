 * HTML Introduction : HTML stands for Hyper Text Markup LanguageHTML is the standard markup language for creating Web pagesHTML describes the structure of a Web pageHTML consists of a series of elementsHTML elements tell the browser how to display the contentHTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

* HTML Elements:The HTML element is everything from the start tag to the end tag:<tagname>Content goes here...</tagname>
* HTML Attributes
All HTML elements can have attributes
Attributes provide additional information about elements
Attributes are always specified in the start tag
Attributes usually come in name/value pairs like: name="value"

* HTML Headings :HTML headings are defined with the <h1> to <h6> tags.<h1> defines the most important heading. <h6> defines the least important heading.

* HTML Paragraphs:The HTML <p> element defines a paragraph.A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.
* HTML Styles:The HTML style attribute is used to add styles to an element, such as color, font, size, and more.
*  HTML Text Formatting: HTML contains several elements for defining text with a special meaning.<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text
* HTML Quotation and Citation Elements :In this chapter we will go through the <blockquote>,<q>, <abbr>, <address>, <cite>, and <bdo> HTML elements.
*  HTML Comments :HTML comments are not displayed in the browser, but they can help document your HTML source code.
*  HTML Colors :HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.
*  HTML Styles - CSS :CSS stands for Cascading Style Sheets.

CSS saves a lot of work. It can control the layout of multiple web pages all at once.CSS can be added to HTML documents in 3 ways:

Inline - by using the style attribute inside HTML elements
Internal - by using a <style> element in the <head> section
External - by using a <link> element to link to an external CSS file.
* HTML Links:HTML links are hyperlinks.You can click on a link and jump to another document.
* HTML Images :HTML Images Syntax
The HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image
* HTML Favicon:A favicon is a small image displayed next to the page title in the browser tab.
* HTML Page Title:Every web page should have a page title to describe the meaning of the page.

The Title Element
The <title> element adds a title to your page
* HTML Tables :HTML tables allow web developers to arrange data into rows and columns.
* Html Lists:HTML lists are used to group related items together.
There are three types: ordered lists (numbered), unordered lists (bulleted), and description lists (term and description).
They help organize content clearly on a web page.
* HTML Block and Inline Elements : A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.

A block-level element always takes up the full width available (stretches out to the left and right as far as it can).

Two commonly used block elements are: <p> and <div>.

The <p> element defines a paragraph in an HTML document.

The <div> element defines a division or a section in an HTML document.
*HTML class Attribute:
The HTML class attribute is used to specify a class for an HTML element.

Multiple HTML elements can share the same class.

* HTML id Attribute
The HTML id attribute is used to specify a unique id for an HTML element.

You cannot have more than one element with the same id in an HTML document.

*HTML Buttons
Buttons let users interact with a web page. They can submit forms, run JavaScript, or trigger different actions when clicked.
* HTML Iframes
An HTML iframe is used to display a web page within a web page.
* HTML JavaScript
JavaScript makes HTML pages more dynamic and interactive.
* HTML File Paths
A file path describes the location of a file in a web site's folder structure.
* HTML - The Head Element
The HTML <head> element is a container for the following elements: <title>, <style>, <meta>, <link>, <script>, and <base>.

* HTML Layout Elements and Techniques
Websites often display content in multiple columns (like a magazine or a newspaper).
* HTML Responsive Web Design
Responsive web design is about creating web pages that look good on all devices!

A responsive web design will automatically adjust for different screen sizes and viewports.

* HTML Computer Code Elements
HTML contains several elements for defining user input and computer code.
* HTML Semantic Elements: A semantic element clearly describes its meaning to both the browser and the developer.

Examples of non-semantic elements: <div> and <span> - Tells nothing about its content.

Examples of semantic elements: <img>, <table>, and <article> - Clearly defines its content.
*HTML Style Guide
Consistent, clean, and tidy HTML code makes it easier for others to read and understand your code.

Here are some guidelines and tips for creating good HTML code.
*HTML Entities
Reserved characters in HTML must be replaced with entities:

< (less than) = &lt;
> (greater than) = &gt;
* HTML Symbols :Symbols or letters that are not present on your keyboard can be added to HTML using entities.

To add such symbols to an HTML page, you can use the entity name or the entity number (a decimal or a hexadecimal reference) for the symbol:
*What are Emojis?
Emojis look like images, but they are not.

Emojis are letters (characters) from the UTF-8 (Unicode) character set:
*The HTML charset Attribute
To display an HTML page correctly, a web browser must know which character set to use.

The character set is specified in the <meta> tag:

<meta charset="UTF-8">
*A URL is another word for a web address.

A URL can be composed of words (e.g. w3schools.com), or an Internet Protocol (IP) address (e.g. 192.68.20.50).

Most people enter the name when surfing, because names are easier to remember than numbers.
*HTML Forms
An HTML form is used to collect user input. The user input is most often sent to a server for processing.
*HTML Form Attributes
This chapter describes the different attributes for the HTML <form> element.

The Action Attribute
The action attribute defines the action to be performed when the form is submitted.

Usually, the form data is sent to a file on the server when the user clicks on the submit button.
* The HTML <form> Elements
The HTML <form> element can contain one or more of the following form elements:

<input>
<label>
<select>
<textarea>
<button>
<fieldset>
<legend>
<datalist>
<output>
<option>
<optgroup>
* HTML Input Types
Here are the different input types you can use in HTML:

<input type="button">
<input type="checkbox">
<input type="color">
<input type="date">
<input type="datetime-local">
<input type="email">
<input type="file">
<input type="hidden">
<input type="image">
<input type="month">
<input type="number">
<input type="password">
<input type="radio">
<input type="range">
<input type="reset">
<input type="search">
<input type="submit">
<input type="tel">
<input type="text">
<input type="time">
<input type="url">
<input type="week">
*The value Attribute
The input value attribute specifies an initial value for an input field:
*HTML Input form* Attributes
This chapter describes the different form* attributes for the HTML <input> element.

The form Attribute
The input form attribute specifies the form the <input> element belongs to.

The value of this attribute must be equal to the id attribute of the <form> element it belongs to.
* HTML Canvas Graphics
The HTML <canvas> element is used to draw graphics on a web page.

The graphic to the left is created with <canvas>. It shows four elements: a red rectangle, a gradient rectangle, a multicolor rectangle, and a multicolor text.
* HTML SVG Graphics
SVG (Scalable Vector Graphics)
SVG defines vector-based graphics in XML, which can be directly embedded in HTML pages.

SVG graphics are scalable, and do not lose any quality if they are zoomed or resized:
* HTML Multimedia
Multimedia on the web is sound, music, videos, movies, and animations.

*HTML Video
The HTML <video> element is used to show a video on a web page.

*HTML Audio
The HTML <audio> element is used to play an audio file on a web page.

The HTML <audio> Element
To play an audio file in HTML, use the <audio> element:
*HTML Plug-ins
Plug-ins are computer programs that extend the standard functionality of the browser.

Plug-ins
Plug-ins were designed to be used for many different purposes:

To run Java applets
To run Microsoft ActiveX controls
To display Flash movies
To display maps
To scan for viruses
To verify a bank id
*HTML YouTube Videos
The easiest way to play videos in HTML, is to use YouTube.




