# How-To: HTML
A primer on Hypertext Markup Language (HTML) and how to master it in under 60 minutes.

## 1. The Basics
### What is it?
Hypertext Markup Language (HTML) is a standard used to create web pages. It defines the content and structure of a webpage in order for your web browser to display it.

### Who use it?
Web designers and web developers use it to build web pages. In some cases, websites will use other tools and methods of generating HTML but every website you have ever visited uses HTML in some fashion.

### How does it work?
When you visit a webpage, an HTML document is sent to your computer and processed by your web browser. The browser reads through the file and builds the webpage according to the set of elements defined in the document.

### What does it look like?

An HTML document uses the file extension `.html`. The html extension tells your browser that this file is meant to be processed as HTML.

The inside of an HTML document will consist of a series of **HTML Elements**. Each element will usually consist of a few components.

#### The Opening Tag
This indicates the beginning of an element and will include any attributes which modify the element. The opening tag will begin and end with opposing *Angle Brackets* like all HTML tags.

*Example*
```html
<header id="site-header" class="component">
```
This defines the start of a `header` element with the attribute of `id` set to `site-header` and the attribute of `class` set to `component`. I'll discuss this more later.

#### The Closing Tag
This indicates the end of an element. It is differentiated from an opening tag by having a `/` after the first angle bracket.

>*Note: In modern HTML, some elements are self-closing meaning they do not have a closing tag. Sometimes these will be denoted by adding a `/` to the end of the opening tag like this `<br />`*

*Example*
```html
</header>
```

#### The Content
Most elements will feature content in the form of either text or other elements. Elements inside of other elements are called *nested elements*. Most HTML documents will feature many nested elements.

>*Note: Except in certain situations, newlines are ignored by browsers when rendering HTML pages. Elements can begin and end on completely separate lines with no problem.

#### Full Examples

```html

<header id="site-header" class="component">This text is the site header</header>
<p>
  <img class="img-responsive" src="picture.jpg">
 </p>
```

### Misc.
#### Comments
There is another type of tag known as a comment. This is like a regular HTML element except it is not rendered by the web browser. It is used to insert notations into the document that can be read in the source view. Comments start with `<!--` and end with `-->`.

*Example*
```html
<!-- This is a comment that will not be displayed on the webpage. -->
```

#### Doctype
HTML documents will usually start with a Doctype declaration which will usually look like this:

```html
<!DOCTYPE html>
```

This tells the browser this file is using standard HTML syntax and structure and to process it in that way.

## 2. The Elements
### Required Elements
The following elements are required for any standard HTML web page.

#### `<html>`
This is your root element. All other elements (except the doctype declaration) are nested inside this element.

#### `<head>`
This element provides general data to the web browser about the webpage and it's contents. The `<head>` element will display anything on the web page but will modify various things about how your browser displays it. The only elements which may be nested inside are `<meta>`, `<link>`, `<title>`, `<base>`, and `<style>` elements

#### `<body>`
All visible content lives inside this element. Everything nested inside of here, except for comments, will be rendered to the user's screen.

#### A full example
Here is the basic skeleton of an HTML document.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Title of the Website</title>
  </head>
  <body>
    <!-- This is where all of the content will go. -->
  </body>
</html>
```

### Metadata Elements

#### `<style>`
The element defines style rules to be used throughout the web page, in the form of CSS (Cascading Style Sheets). CSS will be explained elsewhere.

#### `<meta>`
This element defines certain metadata fields for the browser to interpret. There are many different examples which I may go into at a later point.

#### `<link>`
This element is used to define a relationship with an external resource. It is usually used to link stylesheets (CSS) from other documents.

#### `<title>`
This element defines the title that will appear at the top of the window or in the web page tab in the web browser.

### Organizational Elements

### Block Elements

### Inline Elements

### Multimedia Elements

### Form Elements

### Table Elements

### Misc. Elements


## 3. The Examples
Coming Soon
