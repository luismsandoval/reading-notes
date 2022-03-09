# Class 8 3/8/2022

## CSS Layout

`display` property determines how an element's children behave

```css
div {
  display: ;
}
```

## Flexbox

Flexbox is used for one-dimensional layouts across a single axis. By default, the elements align next to eachother

```css
div {
  display: flex;
}
```

## Grid

Grid is used for layouts with multi-axis

```css
div {
  display: grid;
}
```

## Flow layout

If not using `grid` or `flex`, elements will display in a normal flow.

### Inline block

Use inline block for some block-level characteristics, but flows inline.

```css
p {
  display: inline-block;
}
```

### Floats

You can use `float` to float an element to the left or right and allow surrounding elements to wrap around it.

```css
img {
  float: left;
}
```

### Multicolumn layouts

Use css multicolumn to make elements like lists take up less scroll space from the browser.

```html
<ul class="example">
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
</ul>
```

```css
.example {
  column-count: 2;
  column-gap: 1px;
}
```

### Positioning

`position` element changes how the element behaves in a normal flow. `relative`, `absolute`, `fixed`, `sticky`
