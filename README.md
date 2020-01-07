# WeatherPy

Click ![here](https://maivey.github.io/Web-Design-Challenge/WebVisualizations/index.html) to go to the deployed project webpage.

A Python script that visualizes the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, uses a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), to create a representative model of weather across world cities.

## Prerequisites
This script requires imports of the following:
```code
import pandas as pd
from IPython.display import display, HTML
```

## Summary

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. Using Python requests, APIs, and JSON traversals, this script answers a fundamental question: "What's the weather like as we approach the equator?"

![Equator](Images/equatorsign.png)

This script builds a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

The notebook does the following:

* Randomly selects **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Performs a weather check on each of the cities using a series of successive API calls.
* Includse a print log of each city as it's being processed with the city number and city name.
* Saves both a CSV of all data retrieved and png images for each scatter plot.


