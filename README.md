# python-api-challenge
This challenge involves two parts:
	1.	WeatherPy: I created a Python script to visualize the weather of over 500 cities of varying distances from the equator, and I visualized the data using scatter plots and performed linear regression analysis. I used the citipy Python library and the OpenWeatherMap API to create a representative model of weather across cities. I used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, I created a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

I computed the linear regression for each relationship. I separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).
	2.	VacationPy: I used the weather data to plan vacations by identifying ideal weather conditions. I integrated with the Geoapify API to locate hotels near cities and visualized the results on an interactive map.
 Steps Completed
	a.	Filter cities that meet specific weather conditions (e.g., temperature, wind speed, cloudiness).
	b.	Use the Geoapify Places API to find hotels within a 10,000-meter radius of each city.
	c.	Create a DataFrame to store the city, country, coordinates, humidity, and hotel name.
	d.	Plot the cities and hotels on an interactive map with hover functionality.
 Outputs
	a.	A CSV file (cities.csv) containing weather data for all cities.
	b.	An interactive map displaying vacation destinations with hotel names and countries in hover messages.
 APIs Used
	1.	OpenWeatherMap API:
	•	Provides weather data for cities.
	2.	Geoapify API:
	•	Used to locate hotels near cities.
