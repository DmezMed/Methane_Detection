# Methane Plume Detection 
Based on [sudshu/Pandey_2023_RSE](https://github.com/sudshu/Pandey_2023_RSE) [1]. This version solves some bugs and restructures the original code.

Code for methane plume detection and quantification using Sentinel-2, Sentinel-3, and Landsat instruments through the multi-band-multi-pass (MBMP) method [2]

## Scripts
Folder containig the necesary scripts and data files. Sentinel3_Utilities.py contains some standalone functions that are used throughout the processing. Sentinel3Class.py contains a class object that is used to analyze the Sentinel-3 observations. MS_XCH4_retrieval.py contains the Sentinel-2 and Landsat methane retrieval code.

## CDSE download data
This notebook downloads automatically Sentinel-3 data for the requested location and dates. The Sentinel Hub API must be configured by the user, see https://www.youtube.com/watch?v=GA50fqbrCo4&list=PLj4KwRQTBlPL3CVwpaBXl3VrO0_V3VX_Q&pp=iAQB

## Sentinel-3 methane
This notebook notebook handles the processing of Sentinel-3 SWIR data. To obtain Sentinel-3 SLSTR observations use CDSE download data

## Sentinel-2 methane
This notebook includes code for both Sentinel-2 and Landsat. This code retrieves satellite data from Google Earth Engine, which requires configuring an Earth Engine Python API.
https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api

## References

[1] S. Pandey et al., “Daily detection and quantification of methane leaks using sentinel-3: A tiered satellite observation approach with sentinel-2 and Sentinel-5p,” Remote Sensing of Environment, vol. 296, p. 113716, Oct. 2023. doi:10.1016/j.rse.2023.113716 

[2] D. J. Varon et al., “High-frequency monitoring of anomalous methane point sources with multispectral sentinel-2 satellite observations,” Atmospheric Measurement Techniques, vol. 14, no. 4, pp. 2771–2785, Apr. 2021. doi:10.5194/amt-14-2771-2021 