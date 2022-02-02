# world-weather-analysis

## Overview
This project helps a user to select vacation destinations based on their preferred weather. It uses python libraries to generate a large set of locations based on random coordinates, then find the city nearest those coordinates. From there, the Open Weather Map API is used to look up the weather conditions at each of those cities, and Google Places to find the nearest hotel to the original coordinates. Cities for which weather or a hotel cannot be found are dropped from the final dataset.

Using the aforementioned resources, user can then input their desired maximum and minimum temperatures for a vacation destination, view a map of all locations in the dataset meeting those paramenters, and generate a map of a roundtrip itinerary between four such cities.

## Resources
* Python in Jupyter Notebook
* Libraries
    - pandas
    - numpy
    - citipy
    - requests
    - gmaps
* APIs
    - Open Weather Map
    - Google Maps, Google Places