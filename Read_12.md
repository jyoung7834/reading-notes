# Docs for the HTML `<canvas>` Element & Chart.js

## The `<canvas>` element

`<canvas id="tuturial" width="15"></canvas>`

The `<canvas>` element has only two attributes, width and height.  These are both optional and can also be set using DOM properties.  When no width and height attributes are specified, the canvas will initally be 300 pixels wide and 150 pixels hight.  The element can be sized arbitrarily by CSS, but during rendering the images is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvaas, it will appear distorted. 

## Rendering Content
The canvas is initially blank. To display something, a script first needs to access the rendering context and draw on it. The `<canvas>` element has a method called getContext(), used to obtain the rendering context and its drawing functions. getContext() takes one parameter, the type of context. For 2D graphics, such as those covered by this tutorial, you specify "2d" to get a CanvasRenderingContext2D.
`var canvas = document.getElementById('tutorial');
var ctx = canvas.getContext('2d');`

The first line in the script retrieves the node in the DOM representing the <canvas> element by calling the document.getElementById() method. Once you have the element node, you can access the drawing context using its getContext() method.
