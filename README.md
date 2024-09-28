# python-api-challenge

 # Weather Analysis Project

This project contains two main files: **WeatherPy.ipynb** and **VacationPy.ipynb**, along with a generated data file **cities.csv** and an output folder containing visualizations (fig1-fig4.png) of the weather data analysis.

## Project Overview

### WeatherPy.ipynb
In this notebook, I analyzed weather data from over 500 cities at varying latitudes. After retrieving data using the OpenWeatherMap API, I created several visualizations, including scatter plots for:

- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

I also computed linear regression for each of these relationships, observing significant trends. For instance, as latitude increased, maximum temperatures tended to decrease, while other variables like humidity and wind speed displayed different patterns.

### VacationPy.ipynb
This notebook focuses on planning ideal vacations based on weather conditions. Using the Geoapify API, I filtered the weather data to identify cities with:

- Maximum temperature between 78°F and 80°F

I visualized these ideal cities on a map, highlighting the first hotel within 10,000 meters of each city using interactive hover messages that display the hotel name and country.

## Data Files
- **cities.csv**: Contains city names and their corresponding weather data.
- **output_data/**: Folder containing generated visualizations (fig1-fig4.png).

## Code Source
The scripts for the weather analysis and vacation planning can be found in:
- **WeatherPy.ipynb**: Contains code for weather data visualization.
- **VacationPy.ipynb**: Contains code for vacation planning based on weather data.
