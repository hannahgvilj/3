
Code of Field Locations in 3km Radius 
"""
Double-click on the history item or paste the command below to re-run the algorithm
"""
 processing.run("native:buffer", {'INPUT':'C:/Users/localuser/Documents/GIS data/fieldwork_locations_25830_gpkg.gpkg|layername=field locations','DISTANCE':3000,'SEGMENTS':5,'END_CAP_STYLE':0,'JOIN_STYLE':0,'MITER_LIMIT':2,'DISSOLVE':False,'SEPARATE_DISJOINT':False,'OUTPUT':'TEMPORARY_OUTPUT'})

Source Landcover data URL: https://livingatlas.arcgis.com/landcoverexplorer/#mapCenter=-3.28600%2C31.34000%2C3&mode=step&timeExtent=2017%2C2021&year=2022&downloadMode=true

Zonal Histogram: 
CRS: EPSG:32630 - WGS 84 / UTM zone 30N
Input parameters:
{ 'COLUMN_PREFIX' : 'LC_', 'INPUT_RASTER' : 'C:/Users/localuser/Documents/GIS data/30T_20230101-20240101.tif', 'INPUT_VECTOR' : 'field_locations_3km_buffered.gpkg|layername=buffered', 'OUTPUT' : 'ogr:dbname=\'C:/Users/localuser/Documents/GIS data/field_locations_3km_buffered_LC_hist.gpkg\' table="output" (geom)', 'RASTER_BAND' : 1 }
Results:
{'OUTPUT': 'C:/Users/localuser/Documents/GIS '
'data/field_locations_3km_buffered_LC_hist.gpkg|layername=output'}
ADD KEY LINK - BLACKBOARD
