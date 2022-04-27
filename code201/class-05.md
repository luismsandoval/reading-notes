# Class 5 2/23/2021

## Images

### Adding an image

To add a an image, we will use a the `<img>` tag. This is an empty element, so there is **no closing tag**.

Inside the `<img>` tag lives the *src* attribute, *alt* attribute, and *title* attribute.

- src: tells the browser where to find the image.

- alt: provides a text description of the image.

- title: provides additional information about the image.

```html
<img src="images/img.jpg" alt="image" title="this is an image">
```

3 rules to live by:

1. Save images in the correct format (i.e. jpeg, gif, png)

2. Save images at the right size

3. Use the correct resolution

**TL;DR**

> Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. Use GIF format for images that contain animations.<sup>1</sup>

### Figure and Figure Caption

We can use figure and figure caption to attach a caption to our image. We will use `<figure>` to contain the images and the caption. Then we will use `<figcaption>` to add our caption.

```html
<figure>
  <img src="images/img.jpg" alt="Lorem ipsum lorem ipsum">
  <br />
  <figcaption>Lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum</figcaption>
</figure>
```

### Color

#### Foreground color

`color` is used to change the color of the text in an element.

```css
h1 {
  color: lightsmoke;
}
```

#### Background color

`background-color`

```css
body {
  background-color: teal;
}
```

#### Color values

- RGB i.e. *(100, 100, 100)*

- HEX i.e. *(#32a8a2)*

- Color name i.e. *(blue)*


### Text

`font-famliy`

`font-size`

`@font-face`

`font-weight`

`font-style`

`text-transform`

`text-decoration`

`line-height`

`text-align`

Source: [JPEG vs PNG vs GIF — which image format to use and when?](https://blog.imagekit.io/jpeg-vs-png-vs-gif-which-image-format-to-use-and-when-c8913ae3e01d)<sup>1</sup>
