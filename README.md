# python-api-challenge

### Part 1: WeatherPy

In the WeatherPy part of this challenge, the goal was to visualize the weather of over 500 cities with varying distances from the equator. The tools used included the citipy Python library, the OpenWeatherMap API, and Python coding skills to create a representative model of weather across cities.

#### Requirement 1: Create Plots to Showcase Relationships

For the first requirement, the OpenWeatherMap API was used to retrieve weather data for cities generated using random geographic coordinates. A series of scatter plots were created to showcase the following relationships:

+ Latitude vs. Max Temperature
+ Latitude vs. Humidity
+ Latitude vs. Cloudiness
+ Latitude vs. Wind Speed

#### Requirement 2: Compute Linear Regression for Each Relationship

For the second requirement, linear regression was computed for each relationship. The plots were separated into Northern Hemisphere (latitude greater than or equal to 0 degrees) and Southern Hemisphere (latitude less than 0 degrees). Linear regression lines, formulas, and r values were included in the plots.

### Part 2: VacationPy
In the VacationPy part of the challenge, the goal was to plan future vacations using weather data skills and visualization tools like geoViews Python library and the Geoapify API.\\


#### Steps Taken:
1. A map was created to display a point for each city in the city_data_df DataFrame. The point's size represented the humidity of each city.
2. The city_data_df DataFrame was narrowed down to find cities with ideal weather conditions, such as max temperature between 21 and 27 degrees, wind speed less than 4.5 m/s, and zero cloudiness.
3. A new DataFrame called hotel_df was created to store city, country, coordinates, and humidity information.
4. For each city, the Geoapify API was used to find the first hotel located within 10,000 meters of the city's coordinates.
5. Hotel names and countries were added as additional information in the hover message for each city on the map.

Feel free to explore the code and visualizations in this repository to gain a deeper understanding of the weather and vacation dataset and its results. If you have any questions or feedback, please don't hesitate to reach out!