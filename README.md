# geodata_pvdcrime

## Introduction

The Providence Crime Dataset is a geodataset created by the Brown University Library [GeoData@SciLi](https://libguides.brown.edu/geodata/) team for the analysis of crimes by location and type through time. It is derived from the [Providence Police Case Log](https://data.providenceri.gov/Public-Safety/Providence-Police-Case-Log-Past-180-days/rz3y-pz8v/about_data), updated nightly with the past 180 days of crime incidents in Providence. Longitude and latitude coordinates were derived from three sources: RIGIS's E911 landmark point layer, the RIDOT geocoder, and Open Street Map. The coordinate source is determined by the format of the location attribute in the original dataset: block number, intersection, or landmark. Locations which do not fall into these categories, including standalone street names, were not geocoded due to their imprecise nature. Successfully geocoded results are stored as a point layer (geocoded_results_[year].shp) in the Rhode Island State Plane (ft-US) coordinate system, EPSG 3438. Results are also available in Excel format (geocoded_results_[year].xlsx), with 'latitude' and 'longitude' columns in WGS 84 (EPSG 4326). Cases which could not be accurately geocoded are stored in no_location_matches_[year].xlsx. Cases are stored in separate files by year. In addition to these output files, this repository includes metadata in the OSM Aardvark standard, documentation, and Python scripts for generating the results.

Note that coordinates in the output files are inexact, particularly for crimes associated with block-level locations in the original datasets. These locations do not represent the precise location where the incident occured.

## Rights and Use

The dataset and associated documentation are licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/) CC BY-NC-SA. You are free to share and to adapt the work as long as you cite the source, do not use it for commercial purposes, and release adaptations under the same license.

*Disclaimer: Every effort was made to insure that the data, which was compiled from public sources, was processed and presented accurately. The creators and Brown University disclaim any liability for errors, inaccuracies, or omissions that may be contained therein or for any damages that may arise from the foregoing. Users should independently verify the accuracy and fitness of the data for their purposes.*

## Results
![Results visualized using QGIS](/results.png)
(will be replaced with a higher resolution image)
