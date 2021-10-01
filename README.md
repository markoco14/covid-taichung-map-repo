# Covid Taichung Map Repo
This is not a functioning repo. It is only intended to simplify viewing the code
related specifically to the Google Maps API version of our covid information map.

The original repo can be found at [covid-taichung/cfiw](https://github.com/Covid-Taichung/cfiw).

## File Guide

### map-v3.html
This is the HTML file for the map page. It contains a script tag which makes fetch requests to get the map data. Then it calls the initMap function to initialize the Google Map. It also contains script tags which link to the JS files that contain the functions that make the map work.

### map-functions.js
This file contains the functions that initialize the map, create the map markers, adds marker icons, and marker descriptions.

### map-marker-toggles.js
This file contains the functions that allow the user to select filters for the map and choose which types of markers they want to see.
*the marker data for the disinfection locations is currently out of date*

### initialize-slider.js
This file contains the code for an input slider we used. We used the Ion Range Slider Plugin which can be [foudn here](http://ionden.com/a/plugins/ion.rangeSlider/)

 
