# weather-visualization
Visualization dashboard for weather analysis.

## Summary

Created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. Exported these visualizations and created an interactive dashboard to view them with the associated analysis.

## Methods
* Using Python within a Jupyter notebook:
  * Randomly select 1000 cities based on latitude and longitude using Citipy.
  * Perform a weather check on each of the cities using a series of successive API calls to OpenWeatherMap.
  * Create scatter plots for temperature, humidity, cloudiness, and wind speed against latitude using Matplotlib and Pandas.
  * Save both a CSV of all data retrieved and png images for each scatter plot.
* Created a dashboard to view these visualizations and analysis using bootstrap stylesheet.

## Data Sources
* [OpenWeatherMap](https://openweathermap.org/)
    * Current weather based on city name.
  
