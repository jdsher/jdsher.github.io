---
layout: post
title: County 2 County
---

Up today: a brief little mapping exercise in leaflet for R, combined with htmlwidget's function `saveWidget` that allows users to create a simple map in leaflet, compile it to HTML and upload onto the web.

The topic of the map is the ACS County-to-County migration models, specifically filtered to show migration to Seattle, Portland, and San Francisco. I also wanted to use the very cool "tricolore" package that allows you to create tri-partite choropleth maps that can depict combinations of three different variables (in this case, the percentages of migrants moving to the three different metros).

<iframe src="https://github.com/jdsher/jdsher.github.io/blob/master/c2c_map.html"
style="width: 100%; height: 450px;"></iframe>
