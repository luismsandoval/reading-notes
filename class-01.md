# Class 1 2/12/2022

## How the Web Works

1. Connect to the web via an **Internet Service Provider** (ISP). Type a domain name into your browser.

2. Computer contacts a network of servers called **Domain Name System** (DNS). These act as a *phonebook* and tell your computer the **IP address** of the requested domain.

3. The number returned to your computer allows your browser to contact the web server that hosts that website. A **web server** is a computer set up to specifically send web pages to users.
 
4. The **web server** sends the page requested to your web browser.

## HTML Structure

> HTML Describes the structure of pages

### Elements

> HTML uses elements to describe the structure of pages

- `<html></html>`: used to indicate that anything in between the tags is HTML code

- `<head></head>`: contains information *about* the page. i.e. `<title>`

- `<body></body>`: used to indicate that anything in between the tags is shown in the main browser.

- `<title></title>`: shown at the top of the browser or in the tab location.

- **Attributes** are used to in some opening tags to give us more information about the contents of that element. These attributes require a *name* and *value*. i.e. `<body lang="en">`

### Extra Markup

- **Doctypes**: This lets the browser know which version of HTML the page is using. i.e. `<!DOCTYPE html>` for HTML5

- **Comments**: Comments are used to help better understand what is going on in the code. Remember, these comments will not be visible on the webpage. i.e. `<!-- this is a comment -->`

- **ID attribute**: This is used to uniquely identify a specific element, essentially giving it a name. Every HTML element can carry an ID attribute. i.e. `<p id="name">`

- **Class attribute**: Like the ladder attribute, Class attributes can be used on any HTML element. The class attribute is used to identify several elements as different than the others. Remember, the class attribute can share the same value among different elements. i.e. `<p class="important">` and `<header class="important">`

- **Block elements**: These elements will always appear to start on a new line. These elements include `<h1>`, `<p>`, `<ul>`, and `<li>`

- **Inline elements**: These elements will always appear on the same line as their neighboring elements. These include `<a>`, `<b>`, `<em>`, and `<img>`

- **Grouping text & elements in a block**: The `<div>` element will allow you to group a set of elements together.

- **Grouping text & elements inline**: the `<span>` element is an inline equivalent of the `<div>`

- **iframes**: Inline frame is window on your webpage that shows another page. Think of a google maps iframe that you might see on the bottom of a business' web page. Inside the iframe ther will be the width, height, and source. i.e.
    ```
    <iframe
    width="100"
    height="100"
    src="link">
    </iframe>

- **Information about your page**: `<meta>` is used in the `<head>` element and contains info about the web page.

### HTML5 Layout

- **Header and foooter**: `<header>` and `<footer>` elements are used for the main header or footer at the top or bottom of the page.

- **Navigation**: `<nav>` element is used to hold the main navigation blocks on a website.

- **Article**: `<article>` element is used for a section of a page that can stand alone. Think of a blog entry, comment, et cetera.

- **Asides**: `<aside>` element has 2 purposes depending on whether or not it is inside an `<article>` element. When used inside an article, it should contain info related to the article but not essential. When outside of an article, the aside element should contain content related to the whole page.

- **Sections**: `<section>` element groups content that is related together. 

- **Heading groups**: `<hgroup>` element is used to group together one or more heading elements so that they act as one heading.

- **Figures**: `<figure>` can be used to used to contain any content referenced from an article. This can include images, videos, graphs, diagrams, et cetera. `<figcaption>` is used to provide a text description inside if the `<figure>` element.

- **Linking around block-level elements**: `<a>` can be used around a block level element that contains child elements to turn the entire block into a link.

## JavaScript

### Designing a Script

1. State your goal

2. Work out individual tasks needed to achieve that goal

3. Break down each task into a sequence of steps to follow

4. Translate these tasks into individual lines of code.

### How a Browser sees a Web Page

1. Recieve a page as HTML code
   - consider each page a seperate *document*

2. Create a model and stores it in memory

3. Uses a rendering engine to show the page

### Scripts for a Web Page

#### Objects & Methods

```
document.write('Good afternoon!');
```

Refer to the block of code above for the following:

- `document` acts as the *object*

- `.` acts as the *member operator*

- `write('Good afternoon!')` acts as the *method*

- `'Good afternoon!'` acts as the *parameters* 

Remember, when the browser comes across the `<script>` element, it will stop loading the HTML and load the script before it loads the remainder of the HTML.