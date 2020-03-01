# class12

## Chart.js
### Installation
you can download the lastest version from github releases or also can be found in installation page.

### Creating a Chart
It's easy to get started with Chart.js. All that's required is the script included in your page along with a single < canvas > node to render the chart. 

#### The < canvas > element
< canvas id="tutorial" width="150" height="150">< /canvas>

#### The grid
coordinate space : Normally 1 unit in the grid corresponds to 1 pixel on the canvas.

#### Drawing rectangles
only supports two primitive shapes: rectangles and paths (lists of points connected by lines).

#### There are three functions that draw rectangles on the canvas :-
1. fillRect(x, y, width, height) draws a field rectangle
2. strokeRect(x, y, width, height) Draws a rectangular outline
3. clearRect(x, y, width, height) Clears the specified rectangular area, making it fully transparent

### Drawing paths
1. Frst, you create the path.
2. Then you use drawing commands to draw into the path
3. once the path has been created, you can stroke or fill the path to render it.

### Lines
For drawing straight lines, use the lineTo() method.
lineTo(x, y) Draws a line from the current drawing position to the position specified by x and y.

### Arcs
To draw arcs or circles, we use the arc() or arcTo() methods.
arc(x, y, radius, startAngle, endAngle, anticlockwise)
arcTo(x1, y1, x2, y2, radius)

### Bezier and quadratic curves
quadraticCurveTo(cp1x, cp1y, x, y)
bezierCurveTo(cp1x, cp1y, cp2x, cp2y, x, y)


### Colors
 If we want to apply colors to a shape, there are two important properties we can use:
 1. fillStyle : Sets the style used when filling shapes
 2. strokeStyle : Sets the style for shapes' outlines.


 ### Transparency
 globalAlpha = transparencyValue


 #### Line styles
 There are several properties which allow us to style lines :-
 1. lineWidth = value : Sets the width of lines drawn in the future
 2. lineCap = type : Sets the appearance of the ends of lines.
 3. lineJoin = type : Sets the appearance of the "corners" where lines meet.
 4. miterLimit = value :Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.
 5. getLineDash() : Returns the current line dash pattern array containing an even number of non-negative numbers.
 6. setLineDash(segments) : Sets the current line dash pattern.
 7. lineDashOffset = value : Specifies where to start a dash array on a line.




