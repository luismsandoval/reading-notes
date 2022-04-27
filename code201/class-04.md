# Class 4 2/21/2022

## HTML Links

Links are created by using the `<a>` element and the link is specified by `href=""`

```html
<a href="https://www.google.com/"> Google </a>
```

### Links to other sites

To link to another website, we must use absolute URLs, like the example above.

### Links to other pages on the same site

To link to a page on the same site, we can use relative links.

```html
<a href="about-me.html"> About me </a>
```

### Email links

To create a link that opens the email program to a specific email, we use `mailto:`

```html
<a href="mailto:connect@me.com"> Contact me </a>
```

### Opening a link in a new window

To have a link open in a new window, we will use the `target` attribute with a value of `_blank`

```html
<a href="https://www.google.com/" target="_blank"> Google </a>
```

### Linking to a specific part of a page

To link a user to a specific part of the page, for example, from the bottom of the webpage back to the top, we will use that elements ID tag.

```html
<a href="#top"> Back to top </a>
```

## Layout

### Some key concepts

**Building blocks**:

- Block level elements: Start on a new line

- Inline elements: Flow between surrounding elements

**Containing Elements**:

When a block element is nested inside another box element, the outer element is the *containing element*

### Controlling the elements

- Normal flow: This is the HTML standard. Every block element uses a new line, pushing each element further and further down the webpage.

- Relative positioning: This moves an element relative to its normal flow position.

- Absolute positioning: This positions the element in relation to its container, and removes it from normal flow, meaning it will not affect the positioning of other elements.

- Fixed positioning: This positions the element in relation to the browser window. For example, a scrolling header.

- Floating elements: Floating allows you to place an element to the far left or right and allow other elements to flow around it.

## JavaScript Functions

A function is a group of statements put together to perform a specific task.

### Declaring a function

```javascript
function myFunction() {
  document.write('Hello world');
}
```

### Calling a function

```javascript
myFunction();
```

### Parameters

Parameters are used like variables in a function, and give the function specific information.

```javascript
function myFunction(parameter1, parameter2) {
  document.write(parameter1 + parameter2);
}
```

To call a function that needs information, simply give value to the parameters, making them arguments.

```javascript
myFunction('Hello' + 'world');
```
