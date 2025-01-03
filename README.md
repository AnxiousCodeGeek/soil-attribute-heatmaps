# Heatmap Generation from Soil Attribute Data

This repository contains a Python script that generates heatmaps based on environmental data collected from various devices. The script reads data from CSV files, processes it to filter outliers, and creates visual heatmaps using the Folium library. The generated heatmaps are saved as HTML files, and relevant data is stored in JSON format.

## Features

 - Reads environmental data from CSV files.
 - Cleans and processes data to remove invalid entries.
 - Calculates distances between data points to filter outliers.
 - Generates heatmaps for various environmental attributes (e.g., pH, moisture, nitrogen).
 - Saves heatmaps as HTML files and outputs relevant data in JSON format.

## Requirements

 - ```Python 3.x```
 - ```pandas```
 - ```folium```
 - ```numpy```
 - ```scipy```
 - ```shapely```
 - ```geopandas```
 - ```firebase-admin```
