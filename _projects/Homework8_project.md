---
name: Homework 8
tools: [Python, HTML, vega-lite, altair]
image: assets/pngs/cars.png
description: This is my Homework 8 project!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Homework 8

Here is my combined charts for Homework 8:

```
<vegachart schema-url="{{ site.baseurl }}/assets/json/combinedCharts.json" style="width: 100%"></vegachart>
```

<vegachart schema-url="{{ site.baseurl }}/assets/json/combinedCharts.json" style="width: 100%"></vegachart>

# Write Up for Chart 1

"For my first visualization, I chose to do a histogram that displays a breakdown of the count of records for each county in the building inventory dataset. For the scales, I chose to just do a standard height of 300, but decided to up the width scale in order to be able to clearly read each of the county names with no overlap. I chose bar marks because they are simple and easy to read and interpret, especially for the goal of this visualization."(Homework 7 writeup). I used the graph and same data set that I used in Homework 7, but altered it to get things to work with Altair. I had to alter the first line of code after importing Altair, and also had to alter the last line of the original Homework 7 code, in order to get it to work. For the interactivity of this graph, I used the "click" interaction, which allows the user to click on any of the bars in the bar chart and see just that bar highlighted. This allows for easier reading of any specific data that the user may be wanting to look at, without being overwheled by all of the charts. I did not have to alter any data analysis within this dataset.

# Write Up for Chart 2

"For my second visualization, I chose to use the rect vega-lite plot to display the number of buildings in each county distributed by square footage. I decided to use 40 bins in order to distribute the data more granularly. I also increased the height to 1000 to be able to read all of the counties with no overlap, and increased the width to 1000 to give a bigger range of square footage numbers"(Homeowrk 7 writeup). I used the graph and same data set that I used in Homework 7, but altered it to get things to work with Altair. I had to alter the first line of code after importing Altair, and also had to alter the last line of the original Homework 7 code, in order to get it to work, just as I did with the first graph. I also combined both graphs in a side by side view so that they could be saved together within my files.

# Resources Used

Link to the data set used: https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv

Link to the prep notebook used for reference: https://uiuc-ischool-dataviz.github.io/is445_bcubcg_fall2023/nbv.html?notebook_name=%2Fis445_bcubcg_fall2023%2Fweek10%2FinClass_week10.ipynb

Link to Homework 7 referenced: https://starboard.gg/nb/n2P5pOK

Source used for interactivity "click": https://medium.com/analytics-vidhya/interactive-data-viz-using-altair-873139771fe2

## Search The Data & Methods

Below is where we can put some links to both the data and the analysis code as buttons:


<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link=""https://github.com/cbarnes1230/online_cv_public/blob/main/python_notebooks/Homework_8.ipynb" text="The Analysis" %}
</div>

