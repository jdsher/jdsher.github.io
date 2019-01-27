---
layout: post
title: More Shiny stuff
---

In the interest of just slappin all of my Shiny cards on the table, here are the links to the other Shiny apps I've created so far in my R journey (that I can reasonably share).

[Mobility App](https://jdsher.shinyapps.io/MobilityApp/)
- So called because it was an attempt to investigate corridors of unmet mobility needs in eastern King County, using LODES Data, route performance tables, and vanpool OD records. (Basically, where is there lots of concentrated commutes that KCM is perhaps not satisfying) Not an easy mixture of elements! Approximately six months removed, I now see a lot of issues with the arrangement of the app, and it's extremely unituitive (but to my credit it was intended to be combined with robust documentation and explanatory guides and... yeah it's pretty dang arcane). Still, the development process allowed me to muck around with the fantastic [stplanr package](https://cran.r-project.org/web/packages/stplanr/index.html) by the amazing Robin Lovelace, which is largely built around using OpenStreetMap API services to swiftly create least-cost-path layers from origin-destination data. Great package, and I hope to dabble in it again in the near future... 

[Active Access App](https://jdsher.shinyapps.io/ActiveAccessApp/) 
- Designed to be a visualization and prioritization tool to identify the transit stops in highest need of bike/ped access improvements. The intention was to create layer of walksheds combining equity, connectivity and transit service levels into a unified index score. CIP projects could then be joined to these sheds, with the shed "scores" being imprinted onto the capital project and averaged, thereby granting planners a convenient way to take a first glance at new CIP proposals and filter for projects worth partnering on with jurisdictions. I was ultiamte

