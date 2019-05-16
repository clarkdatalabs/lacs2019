# LACS 2019
Geospatial Data: What you need to know to help your researchers

### data sources:
- [Shapefile for provinces](https://www.bcn.cl/siit/mapas_vectoriales/index_html)



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
