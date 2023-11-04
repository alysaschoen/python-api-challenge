# python-api-challenge

## Overview

This project entails conducting weather data analysis using Python, with the goal of investigating the relationship between weather variables and latitude. The analysis is split into two separate Jupyter notebooks: WeatherPy.ipynb and VacationPy.ipynb, each dedicated to specific analytical aspects.

## Weather
### Data Retreival
- Generates random geographic coordinates and retrieves weather data for various cities using the OpenWeatherMap API.
- Store the data in a Pandas DataFrame and saves as a CSV file

### Visualizations
- Create scatter plots to show the relationship between weather variables (listed below) and latitude
- Perform Linear Regressions to find the correlation between variables (listed below), latitude, and hemisphere.

### Weather Variables
 1. Temperature
 2. Humidity
 3. Cloudiness
 4. Wind Speed

## Vacation
- Create a Heat Map displaying humidity levels for various cities generated from Geoapify
- Use Geoapify to locate the closest hotel within 10,000 metres of coordinates

## API's Utilized
- Open Weather Map
- Geoapify

## Libraries Utilized
- pandas
- matplotlib
- numpy
- hvplot
- requests
- scipy.stats
- termcolor 

