# CH.15:Layout
## Key Concepts in Positioning Elements:
## Building Blocks
### CSS treats each HTML element as if it is in its own box. This box will either be a block or an inline box. Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text. You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors.

## Controlling the Position of Elements:
<h2>1. Normal flow<h2>
 
### In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow, but the syntax would be: position: static.

<h2>2.Relative Positioning<h2>

### Relative positioning moves an element in relation to where it would have been in normal flow.

<h2>3.Absolute positioning<h2>

### When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. 