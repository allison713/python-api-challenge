# API Challenge 6

# WeatherPy

In this challenge, we collected data from the OpenWeatherMap API
using a random generator to create a list of cities. The data 
collected was then organized using a Pandas Dataframe. From the 
Dataframe, scatterplots and linear regressions were completed for 
a variety of relationships between Latitude and weather features.

## Sections

* Generate the Cities List by Using the `citipy` Library
This library takes a randomly generated combination of 
latitude and longitude and produces a city name.

* Use the OpenWeatherMap API to retrieve weather data from 
the cities list generated in the started code.
Using a for loop, cycle through the list of cities and collect:
latitude, longitude, max temp, humidity, cloud cover, wind speed,
country name, and date when the data was collected.

* Organize the collected json into a dataframe.

* Create a variety of scatterplots for global data (all lats)
    - Latitude vs Temperature
    - Latitude vs Humidity
    - Latitude vs Cloudiness
    - Latitude vs Wind Speed

* Create a variety of scatterplots for separate hemispheres. Include Regression line.
    Separate Hemispheres using a .loc logic test for Latitude.
    - Latitude vs Temperature
    - Latitude vs Humidity
    - Latitude vs Cloudiness
    - Latitude vs Wind Speed

# VacationPy

In this challenge, we collected hotel names from the Geoapify API
using a list of cities generated from a provided csv, filtered by
vacation weather preferences. From the original csv and also the 
filtered dataframe, we create an interactive map to display the
information collected.

## Sections

* Import the csv file and read into dataframe.

* Create an interactive map that displays the dataframe information.

* Create a list of "ideal" weather for vacationing. Try to limit the
results to ~ 10 cities.

* By copying some of the columns from this dataframe, create a new, 
limited dataframe.

* Use Geoapify API to search for hotels within 100 km of the cities selected.
    Store the hotel name in a new column in the dataframe.

* Create an interactive map that displays the dataframe information
and includes hotel information in the hover boxes.