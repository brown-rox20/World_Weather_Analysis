# World Weather Analysis

## Background

Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data you’ve already retrieved in this module. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

## Software

- Python 3.9.7
- Jupyter Notebook 6.4.6

## APIs

- OpenWeatherMap
- Google Map Places API
- Google Maps Directions API

## Deliverable 1

Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data you gathered in this module, use your API skills to retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data.

<img src="https://github.com/brown-rox20/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database_screenshot.png" alt="Weather_Database_screenshot.png">

## Deliverable 2

Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

<img src="https://github.com/brown-rox20/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png" alt="WeatherPy_vacation_map.png">

## Deliverable 3

Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

<img src="https://github.com/brown-rox20/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png" alt="WeatherPy_travel_map.png">

<img src="https://github.com/brown-rox20/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png" alt="WeatherPy_travel_map_markers.png">
