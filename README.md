# Weather Visualization

Visualization dashboard for weather analysis.

## Table of contents

* [Summary](#summary)
* [Technologies](#technologies)
* [Development Process](#development-process)
* [Data Sources](#data-sources)
* [Findings](#findings)
* [Contact](#contact)

## Summary

Created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. Exported these visualizations and created an interactive dashboard to view them with the associated analysis.

## Technologies

### Languages Used

* Python - version 3.7
* HTML
* CSS:
  * Boostrap - version 4.3.1

### Data Extraction and Munging

* Jupyter notebook - version 4.1
* Pandas - version 0.23.4
* Numpy - version 1.15.4
* Requests -  version 2.21.0
* Citypy - version 0.0.5

## Development Process

* Using Python within a Jupyter notebook:
  * Randomly selected 1500 cities based on latitude and longitude using Citipy.
  * Performed a weather check on each of the cities using a series of successive API calls to OpenWeatherMap.
  * Created scatter plots for temperature, humidity, cloudiness, and wind speed against latitude using Matplotlib and Pandas.
  * Saved both a CSV of all data retrieved and png images for each scatter plot.
* Created a dashboard to view these visualizations and analysis using bootstrap stylesheet.

## Data Sources

* [OpenWeatherMap](https://openweathermap.org/):  Current weather based on city name.

## Findings

The only strong relationship on June 26, 2019 among the data occurs between temperature and latitude. There is a strong negative correlation between distance from the equator and temperature, i.e., as you get further away from the equator, a city's maximum temperature gets lower.

## Contact

Created by [Gretel Uptegrove](https://gretelup.github.io/)

