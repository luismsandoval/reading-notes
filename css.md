# CSS

## What is it?

Cascading style sheets (CSS) allow you to  control how HTML elements look in the browser.

## CSS Syntax

Using CSS, we define rules that should be applied to particular elements of the HTML. In the example below, we want to tell CSS that we want the main heading to have red text and be 50px large.

```
h1 {
    color: red;
    font-size: 50px;
}
```

Using the example above, let's break down each part of the code.

- **Selector:** This is what determines which HTML element is going to be styled.
- **{}:** Inside these curly braces will be **declarations**, that take consist of **property** and **value** pairs

## Colors

To set a color you can use different values.

- HEX value ```body {color: #92a8d1;}```

- RGB value ```body {color: rgb(201, 76, 76);}```

- RGBA value ```body {color: rgba(201, 76, 76, 0.6);}```

- HSL value ```body {color: hsl(89, 43%, 51%);}```

- HSLA value ```body {color: hsla(89, 43%, 51%, 0.6);}```
