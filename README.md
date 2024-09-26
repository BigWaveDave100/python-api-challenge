# python-api-challenge

This python challenge contains two jupyter notebooks WeatherPy and VacationPy. Both make calls on API databases OpenWeatherAPI and Geoapify. There are 581 cities in this list from all over the world and any data collected is stored in cities.csv. From this data we can determine if there is any corelation between the data provided from each city.

WEATHERPY

![alt text](image-1.png)

![alt text](image-2.png)

**Discussion about the linear relationship:** 
The regression for the northern hemisphere displays a negative slope showing that the max temperature decreases the further away from the equator the latitude gets. 

The regression for the southern hemisphere displays a positve slope showing that the max temperature increases the closer the latitude gets to the equator. 

![alt text](image-3.png)

![alt text](image-4.png)

**Discussion about the linear relationship:** 
Both of the linear regressions display little to no correlation between latitude and humidity in either the northern or southern hemisphere.

![alt text](image-5.png)

![alt text](image-6.png)

**Discussion about the linear relationship:** 
Both of the linear regressions display little to no correlation between latitude and cloudiness in either the northern or southern hemisphere.

![alt text](image-7.png)

![alt text](image-8.png)

**Discussion about the linear relationship:** 
Both of the linear regressions display little to no correlation between latitude and wind speed in either the northern or southern hemisphere.


VACATIONPY

For this jupyter notebook, I used the same output.csv data to demonstrate where each of the cities collected are on a map and show based on the size of the bubble which cities have a higher or lower humidity.

![alt text](118455EC-080F-420E-A203-237A6F75B0CF.jpeg)

Next, I filtered the cities based on the following criterea: between 27 & 21 degrees C, wind speeds less than 4.5, and cloudiness equal to 0. Then, I added a new column to add in Hotel names in the area of the cities fitting the above criterea. 

![alt text](7C33BCBE-6614-4E3E-94D0-C6408BB47591.jpeg)

Finally, I placed all the cities that fit the criterea on a map and displayed the hotel name if there was one. 

![alt text](649DBCEF-7AD3-4C5F-91E3-4E94A8C8EB21.jpeg)