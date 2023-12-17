Dataset Source: http://archive.ics.uci.edu/dataset/275/bike+sharing+dataset (Donated on 2013-12-20)

This dataset, contributed by Hadi Fanaee Tork and derived from Capital Bikeshare data, focuses on bike sharing systems—modernized alternatives to traditional bike rentals with automated processes for membership, rental, and return. These systems enable users to effortlessly rent and return bikes at different locations. Worldwide, there are over 500 bike-sharing programs, totaling more than 500,000 bicycles. The significance of these systems lies in their impact on traffic, environmental considerations, and public health.

Data Description:

datetime: Hourly date and timestamp
season: 1 = spring, 2 = summer, 3 = fall, 4 = winter
holiday: Indicates if the day is a holiday
workingday: Indicates if the day is neither a weekend nor a holiday
weather:
1: Clear, Few clouds, Partly cloudy, Partly cloudy
2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
temp: Temperature in Celsius
atemp: "Feels like" temperature in Celsius
humidity: Relative humidity
windspeed: Wind speed
casual: Number of non-registered user rentals initiated
registered: Number of registered user rentals initiated
count: Total number of rentals
Project Objective:

The training set covers the first 19 days of each month, while the test set spans from the 20th to the end of the month. The goal is to predict the total count of bikes rented per hour during the test set period using information available before the rental period.

Project Outcome:

Among all models evaluated, Random Forest exhibited optimal performance with the lowest Root Mean Square Error (RMSE) of approximately 59.577 and the highest R-squared value (R2) of about 0.948.






