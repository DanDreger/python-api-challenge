# python-api-challenge

Repository contains two seperate Jupyter Notebook (ipynb) files with two seperate projects:

# Weather
The weatherPy project seeks to correlate temperature, wind, humidity, and cloudiness with lattitude. 

After creating data tables with each of the above variables (fetched from the OpenWeather api), the file creates plots to represent the data. You can see those figures in this directory

# Vacation
The Vacation project takes a random list of lats/lngs, and finds the nearest city. Then it filters these destinations, based on temperatures that are not too hot/cold for vacation. Finally, it finds the nearest hotel (using GeoApify) and adds that hotel to the dataframe containing each destinations location, name, etc. These ideal vacation spots are then plotted on a map around the world
