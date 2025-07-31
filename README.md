# USMin

This repository contains a simple web page for viewing mining-related data from the USGS USMIN database.

## Usage

1. Open `index.html` in a modern web browser.
2. The page loads data for all 50 states directly from the USGS site. To use a different dataset, modify the list of state codes or the `loadShapefile` calls in the script.

## Data sources

Data is hosted by the [USGS](https://mrdata.usgs.gov/usmin/). You can download individual state shapefiles or the full geodatabase from links on that site.

## Notes

Loading the entire dataset in the browser may be resource intensive. For best performance, load data for a single state or convert the geodatabase to a tiled or simplified format.
