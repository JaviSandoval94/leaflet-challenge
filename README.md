# Earthquake Data Web Visualization
## Background
The US Geological Survey (USGS) is in charge of providing scientific data about natural hazards, resource availability, ecosystem health, and impacts of climate and land-use change. USGS scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. One of such resources is their [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php), which provides comprehensive data sets related to geological hazards and phenomena. This feed contains the historic earthquake data, which can be a useful tool to map earthquake locations and details using tools such as Leaflet.<br>
This project is divided into two tasks:<br>
## Step 1: Basic Visualization
This map shows the earthquakes' magnitude and location over a single-layer map. Additional facts are shown using tooltips over the locations. This visualization can be found [here](https://javisandoval94.github.io/leaflet-challenge/Leaflet-Step-1/index.html).

## Step 2: More Data 
The map displays magnitude, location and additional facts tooltips over three different map layers, which can be selected by the user. This visualization also shows the fault lines to correlate them to earthquake locations. This visualization can be found [here](https://javisandoval94.github.io/leaflet-challenge/Leaflet-Step-2/index.html).

# Data set
This data uses the Past 7 Days All Earthquakes data, which can be found the the [USGS GeoJSON feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php). The fault line data source can be found in the [tectonicplates repository](https://github.com/fraxen/tectonicplates) from [fraxen](https://github.com/fraxen).

# Code explanation
To run the code, make sure the have the `static` folder available in the working directory. This contains the `.css` and `.js` files necessary to display the maps in the 
`index.html` templates for each of the map visualizations. Make sure to have the Leaflet dependency enabled.
