# Class 3 2/19/2022

## Lists

There are three types of HTML lists to use. These include orderd lists, unordered lists, and definition lists.

### Ordered lists

- `<ol>` this tag creates the ordered lists.

- `<li>` each item in the list will be nested between this tag.

```
<ol>
    <li> number one </li>
    <li> number two </li>
</ol>
```

### Unordered lists

- `<ul>` this tag creates the unordered lists.

- `<li>` this tag is used the same as the latter

```
<ul>
    <li> bullet </li>
    <li> bullet </li>
</ul>
```

### Definition lists

- `<dl>` this tag is used to create definition lists.

- `<dt>` this tag contains the *definition term*

- `<dd>` this tag contains the definition

```
<dl>
    <dt> term </dt>
        <dd> This is a definition </dd>
    <dt> another term </dt>
        <dd> This is another definition </dd>
</dl>
```

### Nested lists

You can create a sublist by nesting `<li>` inside another `<li>` tag.

```
<ul>
    <li> bullet </li>
        <li> sub bullet </li>
        <li> another sub bullet </li>
    <li> bullet </li>
</ul>
```

## Boxes

Every HTML element lives in it's own box, and in order to affect the appearance of these boxes, we must use some CSS. 

### Anatomy of the box

- **Border**: 

- **Margin**:

- **Padding**:
