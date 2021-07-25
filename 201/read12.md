 # Chart.js  
 + a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.
+ To see how to use chart.js we’re going to create a set of 3 graphs; one will show the number of buyers a fictional product has over the course of 6 months, this will be a line chart; the second will show which countries the customers come from, this will be the pie chart; finally we’ll use a bar chart to show profit over the period.  



#  The canvas element  
+ At first sight a canvas looks like the img element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the canvas element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted. 
+ For example, we could provide a text description of the canvas content or provide a static image of the dynamically rendered content. This can look something like this: 
canvas id="stockGraph" width="150" height="150"
  current stock price: $3.15 + 0.15
/canvas

canvas id="clock" width="150" height="150"
  img src="images/clock.png" width="150" height="150" alt=""/
/canvas

## Drawing shapes with canvas
Now that we have set up our canvas environment, we can get into the details of how to draw on the canvas. By the end of this article, you will have learned how to draw rectangles, triangles, lines, arcs and curves, providing familiarity with some of the basic shapes. Working with paths is essential when drawing objects onto the canvas and we will see how that can be done.
## Applying styles and colors  
we will explore the canvas options we have at our disposal to make our drawings a little more attractive. You will learn how to add different colors, line styles, gradients, patterns and shadows to your drawings.  
## Drawing text  
+ A fillText example :
The text is filled using the current fillStyle.

function draw() {
  var ctx = document.getElementById('canvas').getContext('2d');
  ctx.font = '48px serif';
  ctx.fillText('Hello world', 10, 50);
}