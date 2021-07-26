# World Weather Analysis

## Overview
The main purpose is to add the weather description to the weather data which we are retrieving. Then, we will accept input 
statements to filter the data for user's weather preferences, which will be used to identify potential travel destinations and nearby hotels. 
From the list of potential travel destinations,we need to choose four cities to create a travel itinerary. Finally, using the Google 
Maps Directions API, we will create a travel route between the four cities as well as a marker layer map.

## Results

### Retrieve Weather Data

Using a set of 2000 random latitudes and longitudes, we retrive nearby cities and weather data using an API call.
Using the OpenWeatherMap, we have retrived the current weather description and created the below dataframe.Also exported the DataFrame as a CSV file too.


![Weatherdata_df.PNG](https://github.com/Praveeja-Sasidharan-Suni/World_Weather_Analysis/blob/main/Weather_Database/Weatherdata_df.PNG?raw=true)

### Vacation Search

Using input statements ,we will retrieve customer weather preferences, then will use those preferences to identify potential travel destinations 
and nearby hotels.Then,will show those destinations on a marker layer map with pop-up markers.

The updated Hotel Dataframe:

![Hotel_Dataframe.PNG](https://github.com/Praveeja-Sasidharan-Suni/World_Weather_Analysis/blob/main/Vacation_Search/Hotel_Dataframe.PNG?raw=true)

The marker layer map with a pop-up marker for each city:

![WeatherPy_vacation_map.PNG](https://github.com/Praveeja-Sasidharan-Suni/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG?raw=true)


### Vacation Itinerary 

We will use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible 
travel destinations. Then, will create a marker layer map with a pop-up marker for each city on the itinerary.

The directions layer map:

![WeatherPy_travel_map.PNG](https://github.com/Praveeja-Sasidharan-Suni/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG?raw=true)

The marker layer map with a pop-up marker for each city:

![WeatherPy_travel_map_markers.png](https://github.com/Praveeja-Sasidharan-Suni/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png?raw=true)

## Summary

By generating random Latitudes and Longtiudes,we created a city dataframe, containing current weather description. 
Using the data frame and cutomer preferred inputs ,we could generate a data frame containing country,city, current weather description and 
hotels name.Also we have created a Customer Travel Destinations Map too .Finally using the preferences of our cutomers,
we created a Travel Itinerary Map on selected cities and a pop-up marker for each city on the itinerary using the Google Directions API.The scope of this 
analysis in immense that, we can utilise it to plan our trips based on preferred cities,hotels,countries & weather conditions.


