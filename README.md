# python-api-challenge
Use APIs to extract and analysis weather and geo data

## Background
Employed Python scripts and APIs to visualize the weather of over 500 cities of varying distances from the equator. Representative models were created of the weather characteristics across the cities. Extracted the nearest hotel to a select list of "ideal" vacation destinations and plotted the cities on a map.


## Approach

 - WeatherPy
    - Generated over 500 random geographic coordinates.
    - Employed CityPy library to determine the nearest city to each latitude and longitude combination.
    - Created scatter plots to depict the relationship between latitude and weather variables: temperature, humidity, cloudiness and wind speed.
    - Computed linear regression for each relationship for the Northern Hemisphere and Southern Hemisphere using a defined function to compute the plots.
 - VacationPy
    - Used geoViews Python library to create map visualizations of the 500 cities from the WeatherPy analysis.
    - Narrowed the list of cities to under 100 "ideal vacation destinations" based on temperature above 70 degrees and humidity less than 25%.
    - Used Geoapify API to find the nearest hotel within 10,000 meters of each vacation destination city.
    - Used geoViews to create map visualizations of the vacation cities and added the nearest hotel to the hover message for each city on the map.

## APIs Used for Data Analysis
 - OpenWeatherMap API
 - Geoapify API
