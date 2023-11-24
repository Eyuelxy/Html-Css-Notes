# CSS

CSS is the language we use to style a Web page.

CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.

---

# What is CSS?

- CSS stands for Cascading Style Sheets
- CSS describes how HTML elements are to be displayed on screen, paper, or in other media
- CSS saves a lot of work. It can control the layout of multiple web pages all at once
- External stylesheets are stored in CSS files

A CSS rule consists of a selector and a declaration block.

# Example

```css
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
```

---

# CSS Syntax

![https://www.w3schools.com/css/img_selector.gif](https://www.w3schools.com/css/img_selector.gif)

The selector points to the HTML element you want to style.

The declaration block contains one or more declarations separated by semicolons.

Each declaration includes a CSS property name and a value, separated by a colon.

Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.

# Example

In this example all <p> elements will be center-aligned, with a red text color:

```css
p {
  color: red;
  text-align: center;
}

```

# CSS Selectors

CSS selectors are used to "find" (or select) the HTML elements you want to style.

We can divide CSS selectors into five categories:

- Simple selectors (select elements based on name, id, class)
- [Combinator selectors](https://www.w3schools.com/css/css_combinators.asp) (select elements based on a specific relationship between them)
- [Pseudo-class selectors](https://www.w3schools.com/css/css_pseudo_classes.asp) (select elements based on a certain state)
- [Pseudo-elements selectors](https://www.w3schools.com/css/css_pseudo_elements.asp) (select and style a part of an element)
- [Attribute selectors](https://www.w3schools.com/css/css_attribute_selectors.asp) (select elements based on an attribute or attribute value)

# All CSS Simple Selectors

| Selector | Example | Example description |
| --- | --- | --- |
| https://www.w3schools.com/cssref/sel_id.asphttps://www.w3schools.com/cssref/sel_id.asp | #firstname | Selects the element with id="firstname" |
| https://www.w3schools.com/cssref/sel_class.asphttps://www.w3schools.com/cssref/sel_class.asp | .intro | Selects all elements with class="intro" |
| https://www.w3schools.com/cssref/sel_element_class.asp | p.intro | Selects only <p> elements with class="intro" |
| https://www.w3schools.com/cssref/sel_all.asp | * | Selects all elements |
| https://www.w3schools.com/cssref/sel_element.asp | p | Selects all <p> elements |
| https://www.w3schools.com/cssref/sel_element_comma.asp | div, p | Selects all <div> elements and all <p> elements |

# CSS Margins

The CSS `margin` properties are used to create space around elements, outside of any defined borders.

With CSS, you have full control over the margins. There are properties for setting the margin for each side of an element (top, right, bottom, and left).

# Margin - Individual Sides

CSS has properties for specifying the margin for each side of an element:

- `margin-top`
- `margin-right`
- `margin-bottom`
- `margin-left`

All the margin properties can have the following values:

- auto - the browser calculates the margin
- *length* - specifies a margin in px, pt, cm, etc.
- *%* - specifies a margin in % of the width of the containing element
- inherit - specifies that the margin should be inherited from the parent element

# All CSS Margin Properties

| Property | Description |
| --- | --- |
| https://www.w3schools.com/cssref/pr_margin.asp | A shorthand property for setting all the margin properties in one declaration |
| https://www.w3schools.com/cssref/pr_margin-bottom.asp | Sets the bottom margin of an element |
| https://www.w3schools.com/cssref/pr_margin-left.asp | Sets the left margin of an element |
| https://www.w3schools.com/cssref/pr_margin-right.asp | Sets the right margin of an element |
| https://www.w3schools.com/cssref/pr_margin-top.asp | Sets the top margin of an element |