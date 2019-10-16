---
layout: page
title: Test Map
subtitle: 
linktormd: true
leafletmap: true
always_allow_html: yes
---


``` r
print(2*pi)
```

    ## [1] 6.283185

``` r
library(leaflet)

m <- leaflet() %>%
  addTiles() %>%  # Add default OpenStreetMap map tiles
  addMarkers(lng=-122.257885, lat=37.872060, popup="My favorite clock")
m  # Print the map
```

<!--html_preserve-->
<div id="htmlwidget-7ab57412f7b1df4d5773" style="width:100%;height:216px;" class="leaflet html-widget"></div>
  <script type="application/json" data-for="htmlwidget-7ab57412f7b1df4d5773">

<script type="application/json" data-for="htmlwidget-12c746c25b2cbb773c59">{"x":{"options":{"crs":{"crsClass":"L.CRS.EPSG3857","code":null,"proj4def":null,"projectedBounds":null,"options":{}}},"calls":[{"method":"addTiles","args":["//{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",null,null,{"minZoom":0,"maxZoom":18,"tileSize":256,"subdomains":"abc","errorTileUrl":"","tms":false,"noWrap":false,"zoomOffset":0,"zoomReverse":false,"opacity":1,"zIndex":1,"detectRetina":false,"attribution":"&copy; <a href=\"http://openstreetmap.org\">OpenStreetMap<\/a> contributors, <a href=\"http://creativecommons.org/licenses/by-sa/2.0/\">CC-BY-SA<\/a>"}]},{"method":"addMarkers","args":[37.87206,-122.257885,null,null,null,{"interactive":true,"draggable":false,"keyboard":true,"title":"","alt":"","zIndexOffset":0,"opacity":1,"riseOnHover":false,"riseOffset":250},"My favorite clock",null,null,null,null,{"interactive":false,"permanent":false,"direction":"auto","opacity":1,"offset":[0,0],"textsize":"10px","textOnly":false,"className":"","sticky":true},null]}],"limits":{"lat":[37.87206,37.87206],"lng":[-122.257885,-122.257885]}},"evals":[],"jsHooks":[]}</script>
<!--/html_preserve-->
