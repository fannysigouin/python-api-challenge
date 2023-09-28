# python-api-challenge

This challenge was completed in two parts: WeatherPy and VacationPy.

## WeatherPy
The goal of WeatherPy was to create a representative model of weather across cities. The OpenWeatherMap API was used to retrieve the weather data for 500 cities. Various scatter plots were then produced from this data to observe the relationship between the latitude and temperature, humidity, cloudiness, and wind speed. Figures for each of these scatter plots were exported and saved in the output_data folder.
Additional linear regression scatter plots were then produced to illustrate the relationship between latitude and temperature, humidity, cloudiness, and wind speed in the Northern vs Southern hemispheres.

## VacationPy
The goal of VacationPy was to use the Geoapify API to plan future vacations. From a list of cities, this API was used to find a hotel located within 10,000 meters of each city's coordinates. The cities' locations were then plotted on a map plot using hvplot to visualize the cities. 

Starter code provided in WeatherPy.ipynb and VacationPy.ipynb was used to complete this challenge.