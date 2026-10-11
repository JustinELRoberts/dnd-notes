---
publish: true
created: 2026-03-09T00:09:47.683Z
modified: 2026-03-26T00:54:06.867Z
published: 2026-03-26T00:54:06.867Z
LocationType:
aliases:
tags:
---

## Map

```zoommap
imageBases:
  - path: Campaigns/Under The Ash/Locations/_img/<%tp.file.title%> Map.png
    name: <%tp.file.title%>
markers: Campaigns/Under The Ash/Locations/_markers/<%tp.file.title%>.markers.json
markerLayers:
  - Default
minZoom: 0.66
maxZoom: 8
width: 100%
height: 532px
resizable: false
render: canvas
id: <%tp.file.title%>-map
```

## Description

<% tp.file.cursor(1) %>
<%await tp.file.move(`Campaigns/Under The Ash/Locations/${tp.file.title}`)%>
