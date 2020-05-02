# Sheet-Driven Mapping
Testing a web map that reads from google sheets. Project page [here](https://spikeroot.github.io/drbcasemap_test/).

## What?
This project is intended to create a web map using Mapbox GL JS and Mapbox Geocoder that can read data from a google sheet and generate geolocated popups. It is based off of [this tutorial](https://www.mapbox.com/impact-tools/sheet-mapper?utm_medium=blog&utm_source=mapbox-blog&utm_campaign=blog%7Cmapbox-blog%7Ccommunity%7Cworld-central-kitchens-map-to-feed-america-9c48dfa003df-20-04&utm_term=community&utm_content=world-central-kitchens-map-to-feed-america-9c48dfa003df) from Mapbox.

## Why?
The purpose of this project is to test an embeddable web map that can display the locations of applications under review for my planning department.

# How?
This project uses Tabletop.JS to read JSON data from a public Google Sheet. It uses this data to set locations for markers and populate popups. It then displays these markers on a custom Mapbox basemap designed to match the aesthetic of the Wellesley town website.
