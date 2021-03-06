# Chart.js :
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. 
They’re easier to look at and convey data quickly, but they’re not always easy to create.
A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.
**To see how to use chart.js** we’re going to create a set of 3 graphs;
* one will show the number of buyers a fictional product has over the course of 6 months, this will be a line chart;
*  the second will show which countries the customers come from, this will be the pie chart; 
*  finally we’ll use a bar chart to show profit over the period.
## Setting up :
The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in.
Then create a new html page and import the script:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <title>Chart.js demo</title>
        <script src='Chart.min.js'></script>
    </head>
    <body>
    </body>
</html>
```
## Drawing a line chart:
To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:
`<canvas id="buyers" width="600" height="400"></canvas>`
## Drawing a pie chart
Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element:
`<canvas id="countries" width="600" height="400"></canvas>`
## Drawing a bar chart
Finally, let’s add  a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart we’ve already added. First, we add the canvas element:

`<canvas id="income" width="600" height="400"></canvas>`
