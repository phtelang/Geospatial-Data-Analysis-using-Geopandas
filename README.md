## Geospatial Data Analysis using Geopandas

I used Geopandas to plot geospatial data. Geopandas dataframes are similar to Pandas dataframes. Geopandas also allows you to create maps quickly and easily. Maps prepared in Python are easily reproducible and can be customized as per our needs. GeoPandas relies on Shapely to perform geometric operations, each country in our case will be encoded like a polygon using Shapely which will be used by Geopandas to plot.

I read the shape file to plot the countries on the world map and also read the csv file containing happiness ranks for all the countries to plot choropleth maps for Happiness Rank, Economic Development, Population Rank and Income Group. 

### Top 20 Most Destructive California Wildfires
I read the shape file to plot the countries on the world map and also prepared the csv file using data from CalFire containing details like the name and cause of the fire, county name, date, acres burnt down etc.
GeoJSON is a popular open standard for representing geographical features with JSON. It describes points, lines and polygons (called Patches in Bokeh) as a collection of features. Each feature can also have a set of properties. Converting the geopandas file with the geometry information into a Json format is required before using Bokeh to plot data. Bokeh converts the GeoJSON coordinates into columns called x and y or xs and ys for plotting.
