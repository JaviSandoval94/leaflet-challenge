# Earthquake Data Web Visualization
## Background
The US Geological Survey (USGS) is in charge of providing scientific data about natural hazards, resource availability, ecosystem health, and impacts of climate and land-use change. USGS scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. One of such resources is their [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php), which provides comprehensive data sets related to geological hazards and phenomena. This feed contains the historic earthquake data, which can be a useful tool to map earthquake locations and details using tools such as Leaflet. This project aims to showcase global earthquake data from the last seven days in a world map visualization and is divided into two tasks:<br>
## Step 1: Basic Visualization
This map shows the earthquakes' magnitude and location over a single-layer map. The visualizations are generated using the Leaflet library for Javascript in the `static/js/logic.js` file and called into the DOM in the `index.html` file. This visualization is displayed over a single, plain layer using circles whose color and size vary according to the recorded earthquake's magnitude. In addition, this interactive map allows for the user to view additional details using the map's tooltips as shown in the figure below.

![leaflet-step-1](https://github.com/JaviSandoval94/leaflet-challenge/blob/master/pictures/leaflet-step-1.PNG)

The complete visualization can be found [here](https://javisandoval94.github.io/leaflet-challenge/Leaflet-Step-1/index.html).

## Step 2: More Data 
This map is prepared to illustrate the realtionship between techntonic plates and seismic activity. In addition to the original USGS GeoJSON data set, a second data set is visualized alongside the original earthquake blobs. Data on techtonic plates can be found at https://github.com/fraxen/tectonicplates. In addition to the earthquake and techtonic plate data, this map allows the user to select the desired layer and background format from the following options:
* Satellite
* Greyscale
* Outdoors

![leaflet-step-2](https://github.com/JaviSandoval94/leaflet-challenge/blob/master/pictures/leaflet-step-2.PNG)

The complete visualization can be found [here](https://javisandoval94.github.io/leaflet-challenge/Leaflet-Step-2/index.html).

## Data set
![usgs-geojson-data](https://github.com/JaviSandoval94/leaflet-challenge/blob/master/pictures/usgs-geojson-data.png)

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed page and pick a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization.

![geojson-response](https://github.com/JaviSandoval94/leaflet-challenge/blob/master/pictures/geojson-response.png)

## Technical details
To run the code, make sure the have the `static` folder available in the working directory. This contains the `.css` and `.js` files necessary to display the maps in the 
`index.html` templates for each of the map visualizations. Make sure to have the Leaflet dependency enabled.
