PDF -> Inkscape SVG -> [d3js](http://d3js.org) Interactive Chart
======

To experiment with how to make static pdf graphics interactive with d3.js, I thought I would explore the workflow using charts from the [BIS Triennial Survey of Central Banks](http://www.bis.org/publ/rpfx13.htm).  Graph 3 seemed like a good starter since there are multiple subplots that would benefit from linking and interactivity.

The workflow for the first experiment was:

1. Open the pdf in [Inkscape](http://inkscape.org)
2. Strip out the chart and save as plain svg
3. Add the svg in an html wrapper
4. Use d3.js to link and interactify the subplots
5. Share this with the world through this repo, [this chart](http://timelyportfolio.github.io/d3_bis/bis_graph3.html), and this [blog post](http://timelyportfolio.blogspot.com/2014/05/pdf-chart-inkscape-svg-d3-interactive.html)

Please feel free to do with it what you want, but I would appreciate seeing what you do with it.
