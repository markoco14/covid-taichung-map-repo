# Covid Taichung Map Repo
This is not a functioning repo. It is only intended to simplify viewing the code
related specifically to the Google Maps API version of our covid information map.

There is no github pages for this repo.

The original repo can be found at [covid-taichung/cfiw](https://github.com/Covid-Taichung/cfiw).

## File Guide

### map-v3.html (root)
This is the HTML file for the map page. It contains a script tag which makes fetch requests to get the map data. Then it calls the initMap function to initialize the Google Map. It also contains script tags which link to the JS files that contain the functions that make the map work. [Link to code](https://github.com/markoco14/covid-taichung-map-repo/blob/main/map-v3.html).

### map-functions.js (map folder)
This file contains the functions that initialize the map, create the map markers, adds marker icons, and marker descriptions. [Link to code](https://github.com/markoco14/covid-taichung-map-repo/blob/main/map/map-functions.js).

### map-marker-toggles.js (map folder)
This file contains the functions that allow the user to select filters for the map and choose which types of markers they want to see. [Link to code](https://github.com/markoco14/covid-taichung-map-repo/blob/main/map/map-marker-toggles.js).
*the marker data for the disinfection locations is currently out of date*

### initialize-slider.js (map folder)
This file contains the code for an input slider we used. Click [Link to code](https://github.com/markoco14/covid-taichung-map-repo/blob/main/map/initialize-slider.js) to see the code and the changes we've made adapting it to our project. 

We used the Ion Range Slider Plugin and their homepage can be [found here](http://ionden.com/a/plugins/ion.rangeSlider/). 

### the related CSS files are also included in the css folder
 
