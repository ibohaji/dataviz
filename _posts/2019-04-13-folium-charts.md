---
title: "Embedding Folium charts"
date: 2019-04-13
published: true
tags: [dataviz, folium]
excerpt: "Embedding interactive Folium charts on static pages using Jekyll."
folium-loader:
  folium-chart-1: ["charts/Focuscrime.html", "400"]
  folium-chart-2: ["charts/percent_no_internet.html", "400"]
toc: true
toc_sticky: true
---

This post will show examples of embedding interactive maps produced using [Folium](https://github.com/python-visualization/folium).

## OSMnx and Street Networks

<div id="folium-chart-1"></div>
<embed 
       type="text/html" 
       src="/Focuscrime.html"
       width="1100"
       height="600"
       >
</embed>


<iframe src="/charts/Focuscrime.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="100%"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>


## Percentage of Households without Internet

<div id="folium-chart-2"></div>

See the [week 10 lecture slides](https://github.com/MUSA-620-Spring-2019/week-10/blob/master/lecture-10.ipynb) for the code that produced these plots.
