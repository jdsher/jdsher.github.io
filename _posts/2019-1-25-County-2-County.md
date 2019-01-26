---
layout: post
title: County 2 County
---

Up today: a brief little mapping exercise in leaflet for R, combined with htmlwidget's `saveWidget` function that allows users to create a simple map in leaflet, compile it to HTML and upload onto the web.

[tern]("../tern.pdf")

The topic of the map is the ACS County-to-County migration models, specifically filtered to show migration to Seattle, Portland, and San Francisco. I also wanted to use the very cool "tricolore" package that allows you to create tri-partite choropleth maps that can depict combinations of three different variables (in this case, the percentages of migrants moving to the three different metros).

<iframe width="100%" height="500" src="../c2c_map.html" frameborder="0"></iframe>
                       
