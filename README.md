# python-api-challenge
This folder contains two different python scripts, WeatherPy and VacationPy.

**WeatherPY**

WeatherPy 
- Calls the Citipy Python library to generate a lists of over 500 cities of varying distances from the equator
- Weatherpy is used to generate and store the weather data for each of these cities
- These cities and their weather data are moved into a Pandas database

Scatterplots:
- Four scatterplots are created to show the relationship between weather variables and the latitude of the city. 
   1. Latitude vs. Maximum Temperature
   2. Latitude vs. Humidity
   3. Latitude vs. Cloudiness
   4. Latitude vs. Wind Speed
   
Linear Regression Plots:
- Eight different plots are generated, for four different relationships.  For each relationship, the data is split into Northern Hemisphere data and Southern Hemisphere data. 
   1. Latitude vs. Maximum Temperature
   2. Latitude vs. Humidity
   3. Latitude vs. Cloudiness
   4. Latitude vs. Wind Speed
   
For these linear regression plots, a report is included describing the data relationships seen in the visualizations. 

**VacationPy**

- This code reads the csv file generated by the previous script, cities.csv. After pulling in that data, it is then displayed in a map.  Each city is marked by a different colored dot, with the size of the dot representing humidity of that city. 
- A ideal lists of cities is generated by using the following conditions:
    - Maximum temperature lower than 80 degrees
    - Maximum temperature higher than 70 degrees
    - Cloudiness lower than 20
    - Humidity lower than 70
- A new data frame is created to store hotel data
- Geoapify is used to search for a single hotel in each city on the ideal list, which is less than 10,000 meters from the coordinates of the city. 
- The map is generated again, this time showing the city name and hotel name on a hover over each dot. 


Code created by Alana Castellano
