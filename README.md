# Intro to Geospatial Data using Python

## Overview
This notebook demonstrates how to read, write, query and perform geospatial calculations and join data. It also includes some tricks to preprocess data for analysis and some tricks to ensure you are computing efficiently.

## Dependencies
<b>Install the follwing dependencies using pip:</b>
* geopandas - For working with spatial data
* shapely - For geometry handling
* rtree - For efficiently querying spatial data
* pyshp - For reading and writing shapefiles
* pyproj - For conversions between projections
* fiona - For making it easy to read/write geospatial data formats
* ogr/gdal - For reading, writing and transforming geospatial data formats
* geopy - For geolocation and associated calculations
* pysal - Spatil econometrics (exploratory spatial and spatio-temporal data analysis, spatial clustering and more)
* descartes - For plotting geometries in matplotlib

<b> Install the additional GitHub packages:</b>
* pandas profiling - Generates profile reports from a pandas DataFrame
	* ``pip install https://github.com/JosPolfliet/pandas-profiling/archive/master.zip``
* geoplotlib - For visualizing geographical data and making maps
	* ``pip install https://github.com/andrea-cuttone/geoplotlib/archive/master.zip``
* missingno - A small toolset of flexible and easy-to-use missing data visualizations
	* ``pip install https://github.com/ResidentMario/missingno/archive/master.zip``

<b> Install the following package using apt:</b>
* libspatialindex-dev

## Dataset
* [Metro Regional Parcel Dataset](https://gisdata.mn.gov/dataset/us-mn-state-metrogis-plan-regional-parcels) (Download Shapefile)
* [Lakes and Rivers - Open Water Features](https://gisdata.mn.gov/dataset/us-mn-state-metc-water-lakes-rivers) (Download Shapefile)
* [Cedar Lake Quality](https://raw.githubusercontent.com/prabodhw96/Geospatial-Analysis/master/cedar_lake_qual.csv)