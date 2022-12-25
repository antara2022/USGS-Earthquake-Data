# leaflet-challenge

During this project, I used concepts that I have learned to develop a way to visualize USGS (United States Geological Survey) data that will allow the USGS to better educate the public and other government organizations on issues facing our planet. First, for Part 1: I created an Earthqake Visualization to visualize an earthquake dataset. First, to get my dataset, I visited the USGS GeoJSON Feed (http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and chose a dataset to visualize. Next, I used the URL of this JSON to pull in the data for the visualization. Furthermore, to import and visualize the data, we used Leaflet to create a map that plots all the earthqkaes from the dataset based on their longitude and latitude. The data markers reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes appeared larger, and earthquakes with greater depth appeared darker in color. Next, popups were included that provided additional information about the earthquake when its associated marker is clicked. I also created a legend that provided context for my map data.

# Visualization

![map](https://user-images.githubusercontent.com/112270155/209447083-943ea7a0-8be2-41cf-bc26-bbea31914962.png)

# Leaflet-Part-1

This folder contains index.html, the default page of my analysis. This folder also contains the folder Images, which contains the map that was created. This folder also contains the folder static, which contains the folders css and js. The css folder contains style.css, while the js folder contains choropleth.js, config.js, leaflet-heat.js and logic.js.
