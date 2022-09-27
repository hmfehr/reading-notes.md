# Readings: Chart.js, Canvas

## JavaScript Canvas

1. What does the `<canvas>` allow a developer to acheive?

- HTML5 features the `<canvas>` element that allows you to draw 2D graphics using JavaScript.
The `<canvas>` element requires at least two attributes: *width* and *height* that specify the size of the canvas:

2. What is the importance of the closing `</canvas>` tag?
- Unlike the `<img>` element, The <canvas> element requires the closing tag `</canvas>`. Any content between the opening and closing tags is fallback content that will display only if the browser doesn’t support the `<canvas>` element.

3. Explain what the `getContext()` method does.
- The `getContext()` takes one argument which is the type of context. For example, you use the "2d" to get a 2D rendering context object, which is an instance of the `CanvasRenderingContext2D` interface. EX:
  `let canvas = document.querySelector('#canvas');
let ctx = main.getContext('2d');`
  
  
  ## Chart.js Documentation
  
 1. What is Chart.js and how it can be brought into your project?
* Chart.js is a way to creat different types of charts using js. This can be used like a normal graph application that you create yourself.
  
2. List 3 different Chart types you can create using Chart.js.
* Doughnut and pie charts
* line chart
* bar chart
  
## Easily Create Stunning Animated Charts with Chart.js
  
1. What are some advantages to displaying data via a chart over a table?
* Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.
  
2. How could Chart.js aid your previously created applications visually?
* this can dispay a more visually appealing chart data for the products clicked by the user in my odd products
