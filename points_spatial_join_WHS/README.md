# Mapping the UNESCO World Heritage sites

## Task 1 Mapping the World Heritage sites as points
Download data and unzip to your working folder.
1) Add csv-file to QGIS
2) Add base-maps. There are some nice [base-maps collated by Klas Karlsson](https://github.com/klakar/QGIS_resources/blob/master/collections/Geosupportsystem/python/qgis_basemaps.py) 
3) Change the coordinate system to Robinson (EPSG: 54030) which distorts the areas less than WGS84 mapped as Plate Carree
4) Visualise WH sites by category and the years of inscription

## Task 2 Mapping the World Heritage sites in countries
1) Add country borders ne_10m_admin_0_countries.shp
2) Join attributes by location (summary) with one to many option
3) Visualise countries by the count of WH sites per country

## Task 3 Mapping the World Heritage sites in hexagons
1) Create hexagonal grid
2) Join attributes by location (summary) with one to many option
3) Visualise countries by the count of WH sites per hexagons

## Task 4 Mapping the World Heritage sites as heatmap
1) Change the WH layer symbology to heatmap
2) Create lat-lon grid
3) Make looking nice :-)

### Data used in this workshop: 
World Heritage List [World Heritage List](http://whc.unesco.org/en/syndication) and country borders from [Natural Earth](https://www.naturalearthdata.com/) 
