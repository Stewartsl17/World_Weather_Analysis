# World_Weather_Analysis

## Project Overview

For this project, we used Python and API Keys to retrieve weather data, create a map with a variety travel destination map, and finish with an itinerary map. 

### Resources 

* Data Source: Vacation_Search_starter_code.ipynb, Vacation_Itinerary_starter_code.ipynb, ride_data.csv, config.py, WeatherPy_Database.csv, WeatherPy_vacation.csv
* Software: Jupyter Notebooks

## Results

First, we generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and performed an API call with the OpenWeatherMap. Then, we retrieved the current weather description for each city using the coordinates from our sent. 

Here is the resulting dataframe: 

![](https://github.com/Stewartsl17/World_Weather_Analysis/blob/master/Image/Weather%20Dest%20List.png)

Next, we were asked to use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Finally, we were asked to show those destinations on a marker layer map with pop-up markers.

The destinations that we pulled were: 
* Rosebud (Country: US)
* Beaupre (Country: CA)
* Pacific Grove (Country: US)
* Russell (Country: US)

### Dataframe of hotels 
![](https://github.com/Stewartsl17/World_Weather_Analysis/blob/master/Image/Travel%20Dest%20-%20Hotels.png)

We then took these hotels and plotted them on a marker layer map which shows the destinations with pop-up markers. 

### Map of hotels 
![](https://github.com/Stewartsl17/World_Weather_Analysis/blob/master/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

![image](https://user-images.githubusercontent.com/66918641/113461955-c3b64780-93ec-11eb-90a1-7d9144283c5f.png)
