# Mapping_Earthquakes

## Overview of Project 

### Purpose
The purpose of this exercise is to create an earthquake map with three different base map styles, and three separate overlays.\
The base map options here are,
- street view
- satellite view
- dark view

The overlay maps include,
- The tectonic plates location on Earth
- all the earthquakes that were recorded around the world in the past 7 days
- the major earthquakes (magnitude greater than 4.5) that were recorded around th world in the past 7 days 

### Resources used
- Data Source: 
1. All earthquakes in the past 7 days : https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
2. Major earthquakes in the past 7 days:
https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson
3. Tectonic plates data:
https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json

- Software: ECMAScript2015, d3.js 4.11.0, Bootstrap v4.0.0, Leaflet 1.7.1, Mapbox access tokens


## Summary
A map was created that displayed tectonic lines, and earthquakes that were recorded around the world in the past seven days. The earthquakes are represented by circle markers where the radius of the circle is proportional to the magnitude fo the earthquake.\
A switch on the upper right hand corner will allow the user to view the base map layer in street, sattelite, or dark mode.\
The user may also choose to display any number of the overlay maplayers that include the tectonic plates, all earthquakes recorded, or just the major earthquakes recorded in the past 7 days.\
A legend below gives the corellation between the color of the circle markers and magnitude of the earthquake.\
Below is a picture of the map, showing the legend, and the options. All the earthquakes recorded, and the plate tectonics are displayed on a street map style layer.

Below is a picture showing all the major earthquakes with a dark base map layer. Notice the earthquake with a magnitude greater than 6 near the right edge.