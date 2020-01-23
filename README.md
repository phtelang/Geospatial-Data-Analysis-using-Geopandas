## Geospatial Data Analysis using Geopandas

I used Geopandas to plot geospatial data. Geopandas dataframes are similar to Pandas dataframes. Geopandas also allows you to create maps quickly and easily. Maps prepared in Python are easily reproducible and can be customized as per our needs. GeoPandas relies on Shapely to perform geometric operations, each country in our case will be encoded like a polygon using Shapely which will be used by Geopandas to plot.

### Finding the Happiest and Most Developed Countries using Choropleth Maps
I read the shape file to plot the countries on the world map and also read the csv file containing happiness ranks for all the countries to plot choropleth maps for Happiness Rank, Economic Development, Population Rank and Income Group. 

### Top 20 Most Destructive California Wildfires
I read the shape file to plot the countries on the world map and also prepared the csv file using data from CalFire containing details like the name and cause of the fire, county name, date, acres burnt down etc. and then used Bokeh to plot the counties on the map of California.

GeoJSON is a popular open standard for representing geographical features with JSON. It describes points, lines and polygons (called Patches in Bokeh) as a collection of features. Each feature can also have a set of properties. Converting the geopandas file with the geometry information into a Json format is required before using Bokeh to plot data. Bokeh converts the GeoJSON coordinates into columns called x and y or xs and ys for plotting.

### Installation
- Download all the source files on your local folder.
- Download the .ipynb (Jupyter file) and place it in the same folder as the source files.
- Install the requirements using pip install -r requirements.txt. (Make sure you use Python 3.)
- Install Geopandas on conda using: conda install -c conda-forge geopandas. This will install all the dependencies.
