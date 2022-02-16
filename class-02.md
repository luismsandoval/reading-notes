# Class 2 2/14/2022

## HTML Text

## Structural Markup

### Headings

HTML uses six levels of headings from `<h1>` to `<h6>` with `<h1>` being used for main headings, `<h2>` being used for subheadings and so on.

- `<h1>This is the main heading</h1>`


- `<h2>`


- `<h3>`


- `<h4>`


- `<h5>`


- `<h6>`

### Paragraphs

Using the `<p>` tag we can make paragraphs. *Remember*, HTML will show each paragraph on a new line!

`<p> Lorem ipsum lorem ipsum lorem ipsum. </p>`

### Bold and Italic

We can wrap a word with the `<b>` tag to make it appear bold, or the `<i>` tag to make it appear italic.

`<p> Lorem <b>ipsum</b> lorem ipsum <i>lorem</i> ipsum. </p>`

### Superscript and Subscript

The `<sup>` tag is used to contain characters that should be superscript and the `<sub>` tag is used on characters that should be subscript.

`<p> E=MC<sup>2</sup> </p>`

`<p> Lorem ipsum lorem ipsum.<sub>1</sub> </p>`

### White space

HTML ignores extra spaces and extra lines that make it easier for someone to navigate the code. This is known as white space collapsing.

## Semantic Markup

Semantic markup are elements that do not affect the structure of the webpage, but do give additional information regarding the element.

### Strong and Emphasis

`<strong>` tag indicates that the contents have a strong importance.

`<em>` tag indicates that emphasis which can subtly change the meaning of its sentence.

### Quotations

`<blockquote>` tag is used for long quotes that can take up a paragraph.

`<q>` tag is used for short quotes. Hit or miss with IE

### Abbreviations and Acronyms

`<abbr>` tag is used for abbreviations and a title attribute would be placed in the opening tag. `<abbr title="Doctor">Dr<abbr>`

### Citations and Defiinitions

`<cite>` element is used to indicate where the citation is from.

`<dfn>` element is used to indicate the defining instance of a word.

### Author Details

`<address>` is used to indicate the contacts of the author.

### Changes to content

`<ins>` is used to show content that has been added to a doc.

`<del>` is used to show content that has been removed from a doc.

`<s>` is used to show content that is no longer relevent.

## Introducing CSS

CSS allows you to create rules that can control every individual element in an HTML file.

CSS rules have two parts: a **selector** and a **declaration**.

```
p{
  color: blue;
}
```

`p` being the selector and the contents inside being the declaration.

**Declarations** are made of two parts: **property** and **value**.

In the example above, `color:` is the property and `blue` is the value of said property.

### Using External CSS

In order to use tell the HTML file where to find the CSS file, we use the `<link>` element and place it in the `<head>` element.

`<link href="stylesheet.css" type="text/css" rel="stylesheet">

### Using Internal CSS

To use CSS inside an HTML doc, you can use the `<style>` element, which will also be placed inside the `<head>` element. The CSS will rules funtion the same.

### CSS Selectors

- Universal: applies to all elements `* {}`

- Type: applies to element name `h1 {}`

- Class: applies to elements with matching class attribute `.class {}` or `p.class {}`

- ID: applies to elements with matching ID attribute `#Outro {}`

- Child: applies to elements that match as a direct child of another `li>a {}`

- Descendent: applies to elements that match as a descendent of that element, NOT JUST THE DIRECT CHILD `p a {}`

- Adjacent Sibling: Applies to elements that is the next sibling of another element `h1+p {}`

- General Sibling: Applies to elements that is a sibling of another, NOT JUST THE NEXT `h1~p {}`

## Basic JavaScript Instructions

### Declaring Variables

To declare a variable we will be using `let`. It will look like this: `let x = 5`
