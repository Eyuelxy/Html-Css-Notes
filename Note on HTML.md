# HTML

# **What is HTML?**

HTML is the standard markup language for creating Web pages.

### **A Simple HTML Document**

```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

# Example Explained

- The `<!DOCTYPE html>` declaration defines that this document is an HTML5 document
- The `<html>` element is the root element of an HTML page
- The `<head>` element contains meta information about the HTML page
- The `<title>` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
- The `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- The `<h1>` element defines a large heading
- The `<p>` element defines a paragraph

# HTML Documents

All HTML documents must start with a document type declaration: `<!DOCTYPE html>`.

The HTML document itself begins with `<html>` and ends with `</html>`.

The visible part of the HTML document is between `<body>` and `</body>`.

# HTML Elements

The HTML **element** is everything from the start tag to the end tag:

Example 

```html
<h1>My First Heading</h1>
```

HTML elements with no content are called empty elements.

The `<br>` tag defines a line break, and is an empty element without a closing tag:

# **HTML Attributes**

- All HTML elements can have **attributes**
- Attributes provide **additional information** about elements
- Attributes are always specified in **the start tag**
- Attributes usually come in name/value pairs like: **name="value"**

# The href Attribute

The `<a>` tag defines a hyperlink. The `href` attribute specifies the URL of the page the link goes to:

```html
<a href="https://www.w3schools.com">Visit W3Schools</a>
```

# The src Attribute

The `<img>` tag is used to embed an image in an HTML page. The `src` attribute specifies the path to the image to be displayed:

```html
<img src="img_girl.jpg">
```

# The width and height Attributes

The `<img>` tag should also contain the `width` and `height` attributes, which specify the width and height of the image (in pixels):

```html
<img src="img_girl.jpg" width="500" height="600">
```

# The alt Attribute

The required `alt` attribute for the `<img>` tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the `src` attribute, or if the user uses a screen reader.

```html
<img src="img_girl.jpg" alt="Girl with a jacket">
```

# The style Attribute

The `style` attribute is used to add styles to an element, such as color, font, size, and more.

```html
<p style="color:red;">This is a red paragraph.</p>
```

# The title Attribute

The `title` attribute defines some extra information about an element.

The value of the title attribute will be displayed as a tooltip when you mouse over the element:

```html
<p title="I'm a tooltip">This is a paragraph.</p>
```

# HTML Table Tags

| Tag | Description |
| --- | --- |
| https://www.w3schools.com/tags/tag_table.asp | Defines a table |
| https://www.w3schools.com/tags/tag_th.asp | Defines a header cell in a table |
| https://www.w3schools.com/tags/tag_tr.asp | Defines a row in a table |
| https://www.w3schools.com/tags/tag_td.asp | Defines a cell in a table |
| https://www.w3schools.com/tags/tag_caption.asp | Defines a table caption |
| https://www.w3schools.com/tags/tag_colgroup.asp | Specifies a group of one or more columns in a table for formatting |
| https://www.w3schools.com/tags/tag_col.asp | Specifies column properties for each column within a <colgroup> element |
| https://www.w3schools.com/tags/tag_thead.asp | Groups the header content in a table |
| https://www.w3schools.com/tags/tag_tbody.asp | Groups the body content in a table |
| https://www.w3schools.com/tags/tag_tfoot.asp | Groups the footer content in a table |

# The <div> Element

The `<div>` element is by default a block element, meaning that it takes all available width, and comes with line breaks before and after.

# Example

A <div> element takes up all available width:

```html
Lorem Ipsum <div>I am a div</div> dolor sit amet.
```