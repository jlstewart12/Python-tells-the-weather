# What's the weather like?

## Part I - Weather

A Python script was developed to visualize the weather of 500+ cities across the world of varying distance from the equator. Data was pulled from [OpenWeatherMap API](https://openweathermap.org/api).

Initial scatter plots showcase the following relationships:

* ### Temperature (F) vs. Latitude

![hotel map](images/fig5.png)

This plot shows cities with the highest maximum temperatures falling between -40 and 20 degrees of latitude and then temperatures falling as the cities lie further away from the equator. The bulk of them are in the Northern Hemisphere.

* ### Humidity (%) vs. Latitude

![hotel map](images/fig6.png)

As indicated in the plot above, there isn't a strong correlation between humidity and city latitude.

* ### Cloudiness (%) vs. Latitude

![hotel map](images/fig7.png)

Cloudiness is completely independent of where a city is located.

* ### Wind Speed (mph) vs. Latitude

![hotel map](images/fig8.png)

Other than a few outliers, most cities experience wind speeds of 0 to 20 mph independant of their distance to the equator.

## Linear Regression on each relationship by hemisphere

* ### Northern Hemisphere - Temperature (F) vs. Latitude

![hotel map](images/fig9.png)

* ### Southern Hemisphere - Temperature (F) vs. Latitude

![hotel map](images/fig10.png)

* ### Northern Hemisphere - Humidity (%) vs. Latitude

![hotel map](images/fig11.png)

* ### Southern Hemisphere - Humidity (%) vs. Latitude

![hotel map](images/fig12.png)

* ### Northern Hemisphere - Cloudiness (%) vs. Latitude

![hotel map](images/fig13.png)

* ### Southern Hemisphere - Cloudiness (%) vs. Latitude

![hotel map](images/fig14.png)

* ### Northern Hemisphere - Wind Speed (mph) vs. Latitude

![hotel map](images/fig15.png)

* ### Southern Hemisphere - Wind Speed (mph) vs. Latitude

![hotel map](images/fig16.png)
