# python-api-challenge
Use APIs to extract and analysis weather and geo data

## Background
Employed Python scripts to visualize the weather of over 500 cities of varying distances from the equator and created respresentative models of weather characteristics.

## Data Description
 - 9 treament drugs and 1 placebo were test in 249 mice over 45 days.
 - One mouse was removed from the data due to duplicate measurements.
 - In the final data set of 248 mice, the ratio of male to female mice was nearly even at 50.4% vs 49.6%, respectively.
 - The final number of observations in the study totaled 1,880 and the observations per drug ranged from 148 to 230, indicating robust sample sizes for each drug tested.
 - The starting measurement for each tumor was ~45 mm3 across all tested treatments.

## Approach

 - WeatherPy
    - Generated over 500 random geographic coordinates.
    - Employed CityPy library to determine the nearest city to each latitude and longitude combination.
    - Created scatter plots to depict the relationship between latitude and weather variables: temperature, humidity, cloudiness and wind speed.
    - Computed linear regression for each relationship for the Northern Hemisphere and Southern Hemisphere using a defined function to compute the plots.

## Files Used for Data Analysis
 - Mouse_metadata.csv
