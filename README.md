# Mapping_Earthquakes

## Overview

The purpose of this project was to build layers on a map starting with a tetonic map overlay. This helped illustrate the location of the plates in relation to earthquakes. First we started with all size earthquakes is the last seven days. The information was obtained from the USGS website and retrieved geographical coordinates. Then the code was changed so that earthquakes greater than a 4.5 magnitude is illustrated. Another purpose of this porject was learning about branching in Github. 

Information that is in the following map not only includes information such as earthquakes and tetonic plates but as a visual practice on making the map more pleasing to the viewer such as satellite and dark mode. Using the knowledge learned about Javascript, Leaflet.js, and geoJSON data, the following map was created:

![Earthquake Map](ChallengeScreenshot.png)


## Resources and Tools:
- Leaflet.js
- D3.json
- Mapbox
- Google\
- Terminal (iOS)

## Folders/Files associated with the entire project:
### Earthquake_Challenge
-index.html: contain HTML, CSS, Leaflet and D3 to show the map
-static/css/style.css: contains css styling
-static/js/challenge_logic.js: contain Javascript code to retrieve earthquake GeoJSON data from USGS and mapbox access token.

### Earthquake_past7days
-index.html: contain HTML, CSS, Leaflet and D3 to show the map
-static/css/style.css: contains css styling
-static/js/logicStep1.js through logicStep5.js: contain Javascript code to retrieve earthquake GeoJSON data from USGS and mapbox access token.

### Mapping_GeoJSON_Linestrings
-The content of this folder is to create map object to Toronto and show airline routes from Toronto

### Mapping_GeoJSON_Points
The content of this folder is to create map object with geographical center of the Earth and show major airport in the map.

### Mapping_GeoJSON_Polygons
The content of this folder is to create map object with center of Toronto and show Toronto neighborhood.

### Mapping_Lines
The content of this folder is to create the map object with center at the San Francisco airport and create airline routes




