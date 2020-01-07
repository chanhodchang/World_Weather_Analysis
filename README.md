# World_Weather_Analysis
Using Jupyter Notebook and APIs to gather weather data

## Project Overview
Used weather_api to gather information about weather data in cities around the world. 

1. Used the random function in python to generate random numbers used as Latitudes and Longitudes.
2. Citipy was then used to formulate these random coordinates as either real cities or blank coordinates.
3. This data is then used to create a dataframe of cities around the world.
4. The dataframe was then linked to the OpenWeather API to gather weather information about the generated cities.
5. The Google Maps API was then used to create a Google map of the random cities and listed out the different weather conditions.

## Resources
- Data Source: OpenWeather API, Google Maps Cloud Platform API, cities.csv, WeatherPy_vacation.csv, WeatherPy_challenge.csv
- Software: Python 3.6.1, conda 4.7.12

## Summary
The data was then used to create a vacation itinerary that displayed hotels and weather conditions of potential vacton destinations.
- The python input function was used to grab specific data for desired vacation cites from the user such as minimum temperature, maximum temperature, whether they want rain or not, and whether they want snow or not.
- This inputs then created a specific dataframe that used loc to display the desired results.
- From that a desired country was selected and four cities within that country.
- Using Google Maps Cloud Platform, a travel map was created seen in WeatherPy_travel_map.png in the challenge_weather_data folder.
- Google maps was also used to display info about weather and hotel info seem oin WeatherPy_travel_map_markers.png in the challenge_weather_data folder.