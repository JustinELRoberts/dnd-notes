---
LocationType:
Sublocations:
aliases:
tags:
---
## Map
```zoommap
imageBases:
  - path: Campaigns/Under The Ash/Locations/img/<%tp.file.title%> Map.png
    name: <%tp.file.title%>
markers: Campaigns/Under The Ash/Locations/markers/<%tp.file.title%>.markers.json
markerLayers:
  - Default
minZoom: 0.66
maxZoom: 8
wrap: false
responsive: false
width: 100%
height: 532px
resizable: false
resizeHandle: native
render: canvas
id: <%tp.file.title%>-map
```
## Description
<% tp.file.cursor(1) %>
<%await tp.file.move(`Campaigns/Under The Ash/Locations/${tp.file.title}`)%>