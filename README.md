# LACS 2019
Geospatial Data: What you need to know to help your researchers

### data sources:
- [data in Google drive](https://drive.google.com/drive/folders/1Sos_3P9Fj6x8pQxVIGFXc3AnxSzm5QXd)
- [WMTS layer of Provincia de Valparaiso map](https://maps.georeferencer.com/georeferences/144687739730/2017-10-31T20:20:56.574603Z/wmts?key=tskgL72gFmp9cVgl5MUH&SERVICE=WMTS&REQUEST=GetCapabilities), [Information about Provincia de Valparaiso map](https://davidrumsey.georeferencer.com/maps/776038519263/)


# Part I: Working with Geographic Data
- Download and unzip roads
- Open QGIS
- Add roads
- Install OpenLayers plugin
- Add OpenStreetMap basemap
- Add Bing Aerial basemap
- Download and unzip province boundaries
- Add boundaries
- Look at table cleanup video - 40 minutes in 4 minutes!
- Add Excel table to map
- What matches?
- Join based on matching fields
- Export to new file


## Part II: Points in Polygons
- turn off the roads the layer
- download the data from: https://www.ngdc.noaa.gov/nndc/struts/form?t=101650&s=1&d=1
- layer -> add layer -> add delimited text layer
- change to all files
- select the 'results' file
- click on the 'custom delimiters' radio button
- set coordinate system to wgs 84
- once the file is in, we have to reproject it, so:
- right click on 'results' and select save as
- browse to a place to save it and name it 'results_projected'
- for the CRS, select 'EPSG:32719 - WGS 84 / UTM zone 19s
- say 'ok'
- under the vector drop down menu choose 'analysis tools' -> 'count points in polygon'
- It should automatically have 'division_provnicial' as the polygons and 'projected results' as the points'
- Click 'Run'


### data sources
- [Shapefiles for provinces and roads](https://www.bcn.cl/siit/mapas_vectoriales/index_html)
- [Census data for Chile 2017] (http://www.censo2017.cl/microdatos/)

