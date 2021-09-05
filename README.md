# Earthquake_Challenge

## Overview
The purpose of the mapping earthquake challenge was to adjust an already created mapping showing earthquake data by adding tectonic plate lines and major earth quake options to the map using Javascript, Leaflet.js, and geoJSON. The following deliverables were required.
  1.  Add Tectonic Plate Data
  2.  Add Major Earthquake Data
  3.  Add an Additional Map
  
## Resources
  - See Earthquake_Challenge Folder
  - Software & Data Libraries: Visual Studio, HTML, CSS, Javascript, geoJSON, & Leaflet.JS
  - Code
    - [Challenge_Logic.js](https://github.com/sbretag/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/js/challenge_logic.js)
    - [Index.html](https://github.com/sbretag/Mapping_Earthquakes/blob/main/Earthquake_Challenge/index.html)
    - [Stle.css](https://github.com/sbretag/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/css/style.css)

## Using the map

### Directions and Special notes
![image](https://github.com/sbretag/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Images/Map_Options.png)

    - 3 base layer options are available to select from
      - Satellite
      - Street
      - Dark View
    - Note to avoid duplicative circle markers, uncheck either Earthquakes or Major Earthquakes, the default view shows both
    - Circlemarker radius size is relative to earthquake magnitude

![image](https://github.com/sbretag/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Images/Map_Legend.png)

    - Note that the legend only applies to the "Earthquakes" layer, Major Earthquakes are shown on a different color scale
      - Major Earthquakes greater than 6 magnitude: Red
      - Major Earthquakes greater than 5 magnitude: Orange
      - All other Major Earthquakes: Yellow

### Map Sample Views

#### Sample 1: All Earthquakes shown on satellite map with plate tectonics
![image](https://github.com/sbretag/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Images/Sample_1_AllEarthquakes_Satellite.png)

#### Sample 2: Major Earthquakes shown on dark map with plate tectonics
![image](https://github.com/sbretag/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Images/Sample_2_MajorEq_Dark.png)

