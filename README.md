# Reading and Displaying WMS File on Leaflet Map

[RIVM WMS Data](https://data.rivm.nl/geo/alo/wms) used as an example WMS file.

This file demonstrates the usage of RIVM data as an example WMS file using Leaflet and JavaScript. It includes code to display the layer list container (`#layerListContainer`) on the left side of the page, with a maximum height based on the screen and a vertical scrollbar if necessary. The Leaflet map (`#map`) takes up the remaining available space on the right side.

## Features

- Display of layer list container on the left side of the page.
- Maximum height of the layer list container based on the screen.
- Vertical scrollbar added to the layer list container if necessary.
- Moving selected layers to the top of the list when their respective checkboxes are selected. This ensures that the selected layers are always displayed at the top of the list.
