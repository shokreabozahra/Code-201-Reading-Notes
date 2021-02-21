# Basic usage of canvas
## The (canvas) element:
### he id attribute isn't specific to the (canvas) element but is one of the global HTML attributes which can be applied to any HTML element (like class for instance). It is always a good idea to supply an id because this makes it much easier to identify it in a script.

### The (canvas) element can be styled just like any normal image (margin, border, background…). These rules, however, don't affect the actual drawing on the canvas. We'll see how this is done in a dedicated chapter of this tutorial. When no styling rules are applied to the canvas it will initially be fully transparent.

## The rendering context:
### The canvas is initially blank. To display something, a script first needs to access the rendering context and draw on it. The (canvas) element has a method called getContext(), used to obtain the rendering context and its drawing functions.
<hr>

# Drawing shapes with canvas
## Drawing rectangles
### Unlike SVG, (canvas) only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.

## Moving the pen
### One very useful function, which doesn't actually draw anything but becomes part of the path list described above, is the moveTo() function. You can probably best think of this as lifting a pen or pencil from one spot on a piece of paper and placing it on the next.

<hr>


# Applying styles and colors
## Transparency:
### The globalAlpha property can be useful if you want to draw a lot of shapes on the canvas with similar transparency, but otherwise it's generally more useful to set the transparency on individual shapes when setting their colors.

### Because the strokeStyle and fillStyle properties accept CSS rgba color values, we can use the following notation to assign a transparent color to them.

## Line styles:
### There are several properties which allow us to style lines.

- lineWidth = value
#### Sets the width of lines drawn in the future.
- lineCap = type
#### Sets the appearance of the ends of lines.
- lineJoin = type
#### Sets the appearance of the "corners" where lines meet.
- miterLimit = value
#### Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.
- getLineDash()
#### Returns the current line dash pattern array containing an even number of non-negative numbers.
- setLineDash(segments)
#### Sets the current line dash pattern.
- lineDashOffset = value
#### Specifies where to start a dash array on a line.
## Canvas fill rules:
### When using fill (or clip and isPointInPath) you can optionally provide a fill rule algorithm by which to determine if a point is inside or outside a path and thus if it gets filled or not. This is useful when a path intersects itself or is nested.

<hr>


# Drawing text
## Styling text:
### font = value
- The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.
### textAlign = value
- Text alignment setting. Possible values: start, end, left, right or center. The default value is start.
### textBaseline = value
- Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.
### direction = value
- Directionality. Possible values: ltr, rtl, inherit. The default value is inherit
