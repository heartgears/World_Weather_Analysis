# World_Weather_Analysis
 
This repository features random locations and hotels nearby generated using Google APIs. 

## Overview
**Task**: Collect and analyze weather data across cities worldwide.
**Purpose**: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
**Method**: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data. Your analysis of the data will be split into three main parts, or stages.

## Technologies & Requirements
* Data File: Weather_Py_Vacation.csv, WeatherPy_Database.csv
* Software: Matplotli 3.2.2, Python 3.9, Anaconda 4.8.5, Jupyter Notebook 6.1.4, Pandas

## Results

### Deliverable 1
All of the following information is stored from the API call:

* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
* Weather description (for example, clouds, fog, light rain, clear sky)

The weather data is added to a new DataFrame and exported as WeatherPy_Database.csv into the Weather_Database folder.

## Deliverable 2
* Input statements are written to prompt the customer for their minimum and maximum temperature preferences.
* A new DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped.
* The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped.
* The DataFrame is exported as a CSV file into the Vacation_Search folder and is saved as WeatherPy_vacation.csv.

A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information: 
* Hotel name
* City
* Country
* Current weather description with the maximum temperature

The marker layer map is saved and uploaded to the Vacation_Search folder as WeatherPy_vacation_map.png as seen below:

![Map_1](https://github.com/heartgears/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

## Deliverable 3
* Four DataFrames are created, one for each city on the itinerary.
* The latitude and longitude pairs for each of the four cities are retrieved.
* A directions layer map between the cities and the travel map is created and uploaded as WeatherPy_travel_map.png.
* A DataFrame that contains the four cities on the itinerary is created.

A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as WeatherPy_travel_map_markers.png. Each marker has the following information:
* Hotel name
* City
* Country
* Current weather description with the maximum temperature

![Map_2](https://github.com/heartgears/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
