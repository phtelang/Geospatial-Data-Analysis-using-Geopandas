## Geospatial Data Analysis using Geopandas

I used Geopandas to plot geospatial data. Geopandas dataframes are similar to Pandas dataframes. Geopandas also allows you to create maps quickly and easily. Maps prepared in Python are easily reproducible and can be customized as per our needs. GeoPandas relies on Shapely to perform geometric operations, each country in our case will be encoded like a polygon using Shapely which will be used by Geopandas to plot. 
I read the shape file to plot the countries on the world map and also prepared the csv file using data from CalFire containing details like the name and cause of the fire, county name, date, acres burnt down etc. and then used Bokeh to plot the counties on the map of California.
