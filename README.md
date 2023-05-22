# Python-Api-Challenge
Part I - WeatherPy

Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. 

Build a series of scatter plots to showcase the following :
Temperature(F) vs. Latitude
Humidity(%) vs. Latitude
Cloudiness(%) vs. Latitude
Wind Speed(mph) vs. Latitude

Run linear regression on each relationship :
Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

Data should showcase :
cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.

Part II - VacationPy
Create a heat map that displays the humidity for every city generated from Part I - WeatherPy.
Narrow down the DataFrame to find your ideal weather condition. Zero cloudiness.
Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.

Requirements:
Install citypy in your python environment (https://pypi.python.org/pypi/citipy)
OpenWeatherMap API Key (https://openweathermap.org/) as 'weather_api_key'
Google API Key (https://console.developers.google.com/getting-started) as 'g_key'
Create API Keys and store it in the 'api_keys.py' file before running the Jupyter notebooks.
