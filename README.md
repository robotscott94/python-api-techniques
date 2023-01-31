# python-api-techniques
Various method of pulling data via APIs and doing basic analysis

In this WeatherPy, random values for latitude and longitude are generated, and the citipy package is used to determine the nearest town or city to the sets of coordinates. The open weather api is then used to pull weather data for each city found, and a dataframe is created with information including city name, temperature, wind speed, humidity, cloudiness, and geocoordinates.

Analysis is done on this data frame by creating scatter plots to investigate the relationship between latitude and various weather features. Analysis includes temperature, humidity, cloudiness and wind speed factors.

The data is then split into northern and southern hemispheres, and regression is done using the same four weather factors. The linear relationship between latitude and the four weather factors is discussed beneath the analysis. Graphs and data frames are saved in the output folder when running this notebook.

In VacationPy, the same data is used that was generated in WeatherPy. The cities are plotted on a map, and the markers are scaled by humidity percentage. Next, the list of cities is narrowed by searching for cities that meet specific weather paramters. The geoapify api is used to find the nearest hotel to each city, and a final map is generated to show the location of the 'ideal' cities. A pop-up feature is activated so city data appears when hovering the mouse over a city marker.
