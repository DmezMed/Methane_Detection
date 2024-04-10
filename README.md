# Methane Plume Detection 
Based on [sudshu/Pandey_2023_RSE](https://github.com/sudshu/Pandey_2023_RSE). This version corrects some issues of the original code.

Code for methane plume detection and quantification using Sentinel-2, Sentinel-3, and Landsat instruments.

## Scripts
Folder containig the necesary scripts and data files. Sentinel3_Utilities.py contains some standalone functions that are used throughout the processing. Sentinel3Class.py contains a class object that is used to analyze the Sentinel-3 observations. MS_XCH4_retrieval.py contains the Sentinel-2 and Landsat methane retrieval code.

## CDSE download data
This code downloads automatically Sentinel-3 data for the requested location and dates. The Sentinel Hub API must be configured by the user, see https://www.youtube.com/watch?v=GA50fqbrCo4&list=PLj4KwRQTBlPL3CVwpaBXl3VrO0_V3VX_Q&pp=iAQB

## Sentinel-3 methane
This notebook notebook handles the processing of Sentinel-3 SWIR data. To obtain Sentinel-3 SLSTR observations

## Sentinel-2 methane
This notebook includes code for both Sentinel-2 and Landsat. This code retrieves satellite data from Google Earth Engine, which requires configuring an Earth Engine Python API.
https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api
