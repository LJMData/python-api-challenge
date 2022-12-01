# python-api-challenge

This Python script has been used visualize the weather of over 500 cities of varying distances from the equator. The code uses the OpenWeather API to get data to create a series of scatter plots which showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

It uses the same data set to compute the linear regression for each relationship (including the linear regression line, the model's formula, and the r values). It has separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).

# Findings 

Temperature vs. Latitude Linear Regression Plot
The northern hemisphere shows a negative correlation with an R-value of 0.7 which suggests a strong correlation. The southern hemisphere shows a positive correlation but with an R-value of 0.4 so this is a weak correlation. 
Cities with a latitude of between 0-30 in the northern hemisphere have their max temperature more closely clustered around the line but as the latitude increases the points become more widely dispersed. Cities in the southern hemisphere have a wider spread of max temperatures around the line with several obvious outliers. 
The lowest max temperature was in the northern hemisphere whose axis goes down to 230, with the southern hemisphere having fewer cities around the lower end of its axis which only goes down to 275. 

Humidity vs. Latitude Linear Regression Plot
Both the northern and southern hemispheres have a wide dispersion of their humidity figures around the line, with r values of 0.1 suggesting a very weak correlation. 

Cloudiness vs. Latitude Linear Regression Plot
Both the northern and southern hemispheres have a wide dispersion of their cloudiness figures around the line, with r values of 0.1 suggesting a very weak correlation. Both hemispheres have points clustered around the top and the bottom of the scales which means there is a wide spread of data affecting any measures of centrality. 

Wind Speed vs. Latitude Linear Regression Plot
The northern hemisphere has many of the points clustered around the bottom of the scale, however, as the latitude increases to the 60 -80 mark, there is a much wider spread of wind speeds with several being 15m/s plus. This will affect the R-value, which is 0.02 suggesting a very weak correlation, which for the northern hemisphere is positive. The data in the south has a higher r value of 0.2 which suggests a weak correlation, which is negative. As the latitude becomes more negative the city’s wind speeds become more despised with some outliers at the very bottom of the latitude scale. 

# Vacation 
Using the geoViews Python library, and the Geoapify API the code use weather data to plan future vacations. The Maps show weather data of the cities generated in the first activity and the final map shows locations in the norther hemisphere which have suitable weather for a holiday with a husky! hovering over the second map shows potential hotel locations suitable for theses cities. 
