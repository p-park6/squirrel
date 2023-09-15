####
## Team HAAAAWK:
Heather Childers, Patty Park, Liane Chen, Olivia Holt


# LeafMap Example: Visualizing NYC Squirrel Census Data
In this example, we will demonstrate how to use the leafmap package in python to visualize NYC squirrel census data obtained from the Kaggle dataset 'NYC 2018 Squirrel Census'. Leafmap simplifies the process of creating interactive maps and working with geospatial data, making it easy to explore and analyze datasets like this one. Also included are two demo files as examples for how to use leafmap.


### Installing
You can install LeafMap using pip:
pip install leafmap


## Getting Started
### Dependencies
Before you begin, ensure you have the following prerequisites:

Python installed on your machine.
The LeafMap package installed.
Download the NYC Squirrel Census data from Kaggle and save it to your project directory.


## Example
```
#### Create a map centered at a specific location
m = leafmap.Map(location=[37.7749, -122.4194], zoom_start=10)


#### Add a marker to the map
marker = leafmap.Marker(location=[37.7749, -122.4194], draggable=True)
marker.add_to(m)


#### Display the map
m
```

### Mapping backends
Ipyleaflet
Folium
Bokeh
Plotly
Pydeck
KeplerGL


## Key Features
-Create an interactive map
-Customize map height
-Set control visibility
-Change basemaps
-Add XYZ tile layer
-Add WMS tile layer
-Add COG layer
-Add STAC layer
-Add legend
-Add colorbar
-Add GeoJSON
-Add shapefile
-Add KML
-Add GeoDataFrame
-Create heat map
-Save map to HTML
-Add Planet imagery


### License
LeafMap is released under the MIT License.


### Contact
Website: https://leafmap.org
GitHub: https://github.com/giswqs/leafmap
Email: support@leafmap.org


## Source
Wu, Q. (2021). Leafmap: A Python package for interactive mapping and geospatial analysis with minimal coding in a Jupyter environment. Journal of Open Source Software, 6(63), 3414. https://doi.org/10.21105/joss.03414
