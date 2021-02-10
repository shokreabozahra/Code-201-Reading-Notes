# Chapter 5:Images
## Images can improve the design and the appearance of a web page.
## HTML Images Syntax

- The HTML (img) tag is used to embed an image in a web page.

- Images are not technically inserted into a web page; images are linked to web pages. The (img) tag creates a holding space for the referenced image.

- The (img) tag is empty, it contains attributes only, and does not have a closing tag.

### The (img) tag has two required attributes:

- src - Specifies the path to the image
- alt - Specifies an alternate text for the image
## The src Attribute:
### The required src attribute specifies the path (URL) to the image.
## The alt Attribute:
### The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).
## Height & Width of Images:
- You can use the style attribute to specify the width and height of an image.
- Alternatively, you can use the width and height attributes.
- The width and height attributes always define the width and height of the image in pixels.
## Where to Place Images in the Code:
- before a paragraph
- inside the start of aparagraph
-  in the middle of a paragraph
### Browsers show HTML elements in one of two ways:
- Block elements always appear on a new line.
- Inline elements sit within a block level element and do not start on a new line.
###  Aligning Images Horizontally:
#### The align attribute was commonly used to indicate how the other parts of a page should flow around an image. It has been removed from HTML5 and new websites should use CSS to control the alignment of images.
###  Aligning Images Vertically:
#### There are three values that the align attribute can take that control how the image should align vertically with the text that surrounds it:
- top
- middle
- bottom
##  Figure and Figure Caption
Use a (figure) element to mark up a photo in a document, and a (figcaption) element to define a caption for the photo.
- The (figcaption) tag defines a caption for a (figure) element.
- The (figcaption) element can be placed as the first or last child of the (figure) element.
>You should save images at the size you will be using them on the web page and in the appropriate format.

>Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.
<hr>

# Chapter 11: Color
## Background Color
### The CSS background-color property defines the background color for an HTML element.
## CSS Colors:
## RGBA Colors
- RGBA color values are an extension of RGB color values with an alpha channel - which specifies the opacity for a color.
- An RGBA color value is specified with: rgba(red, green, blue, alpha). The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (fully opaque).
## Opacity
- The CSS opacity property sets the opacity for the whole element (both background color and text will be opaque/transparent).

- The opacity property value must be a number between 0.0 (fully transparent) and 1.0 (fully opaque).
## HSL Colors
- HSL stands for Hue, Saturation and Lightness.
- An HSL color value is specified with: hsl(hue, saturation, lightness).
## HSLA Colors
- HSLA color values are an extension of HSL color values with an alpha channel - which specifies the opacity for a color.
- An HSLA color value is specified with: hsla(hue, saturation, lightness, alpha), where the alpha parameter defines the opacity. The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (fully opaque).
>CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.

>CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.
<hr>

# Chapter 12: Text
## Typeface:
1. Serif  fonts have a small stroke at the edges of each letter. They create a sense of formality and elegance.

2. Sans-serif fonts have clean lines (no small strokes attached). They create a modern and minimalistic look.

3. Monospace fonts - here all the letters have the same fixed width. They create a mechanical look. 

4. Cursive fonts imitate human handwriting.

5. Fantasy fonts are decorative/playful fonts.
## Specifying Typefaces:
### font-family
##### The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.

### Font Size
- The font-size property sets the size of the text.

- Being able to manage the text size is important in web design. However, you should not use font size adjustments to make paragraphs look like headings, or headings look like paragraphs.

- Always use the proper HTML tags, like (h1 - h6) for headings and (p) for paragraphs.

- The font-size value can be an absolute, or relative size.

### Absolute size:

1. Sets the text to a specified size
2. Does not allow a user to change the text size in all browsers (bad for accessibility reasons)
3. Absolute size is useful when the physical size of the output is known
### Relative size:

1. Sets the size relative to surrounding elements
2. Allows a user to change the text size in browsers

## Units of Type Size
- Pixels 
- Percentages 
- Ems
### Bold font-weight:
### The font-weight property sets how thick or thin characters in text should be displayed.
## Styling Links
### Links can be styled with any CSS property,also  links can be styled differently depending on what state they are in.The four links states are:
- a:link - a normal, unvisited link.
- a:visited - a link the user has visited.
- a:hover - a link when the user mouses over it.
- a:active - a link the moment it is clicked.

>You can control the space between lines of text,
individual letters, and words. Text can also be aligned
to the left, right, center, or justified. It can also be indented.

> You can use pseudo-classes to change the style of an
element when a user hovers over or clicks on text, or
when they have visited a link

