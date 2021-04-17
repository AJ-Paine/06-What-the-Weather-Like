Python APIs Challenge

This repository was created for DU Data Analytics Bootcamp homework on working with APIs.

WeatherPy
In this challenge I use Jupyter Notebooks to analyze a weather dataset. The data was pulled by randomly generating latitudes and longitudes for over 500 cities and then using the OpenWeatherMap API to pull current weather data for said cities. Pandas and matplotlib were then used to evaluate and create regression models for the relationships beween latitude and several other variables including max temperature, wind speed, humidty and cloudiness.

VacationPy
For the second part of the challenge, the weather data pulled from the OpenWeatherMap API in WeatherPy was imported via csv. This data was used in conjunction with the google places api to identify the hotels in the most ideal vacation locations. The potential vacation locations were identified by setting user based preferences for humidity, temperature, wind speed and cloudiness then using pandas to remove any cities that did not meet those requirements. Lastly, gmaps was implemented to create a heat map of humidity and mark the potential locations with an infobox providing nearest hotel name, city and country.
