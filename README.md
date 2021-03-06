# World_Weather_Analysis

## Overview
The purpose of this new analysis is to revamp the PlanMyTrip app so that a weather description for each area will be added. Individuals will then be able to add their weather preferences, and this will allow the app to identify potential travel destinations along with nearby hotels. A travel itinerary will then be created between four different cities, along with hotels to stay along the way and the travel route. To complete this analysis, I used API's in Jupyter Notebooks. Some of the libraries I have used include:

## Results
 Of the random 2000 latitudes and longitudes generated, I was able to pull down 689 locations with weather information. Of the 689 locations, I was able to pull 132 hotels within the parameters of max temp 90 and min max temp 80. 

![PyBer_Summary_df](/Images/Balanced_Random_Forecast_Classifier_balanced_accuracy_score.PNG)

For this trip, I selected 4 locations close to each other and mapped out paths to get there by driving.

![PyBer_Summary_df](/Vacation_Itinerary/WeatherPy_travel_map.PNG)

The view below, shows the 4 hotels for the trip, the city they are in, the country they are in, and the current weather. 

![PyBer_Summary_df_line_Graph](/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)


## Summary

This is a great example of pulling information from APIs and connecting the data with each other. Pulling from an API for weather and integrating it into a Google API to create visuals on great locations to visit and mapping out routes to get there.
