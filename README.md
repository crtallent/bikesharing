# Bikesharing

## Overview of Bikesharing Project

For this project, we are tasked with proposing to investors that a bikesharing business, such as Citi Bike in New York City, is an excellent endeavor in the city of Des Moines, Idaho.  As there is currently no local bikesharing operations in the area, data from Citi Bike was analyzed to ascertain more information about operating a bikesharing business. Bikesharing data from August 2019 was downloaded in the form of a CSV file and uploaded to Tableau Public for the purpose of the analysis.  The full proposal can be found on the Tableau Public Server, which can be accessed by clicking this [link](https://public.tableau.com/app/profile/crystal.tallent/viz/Bikesharing_16456548744410/Story1?publish=yes).

## Resources

* Software: Python 3.7.11, Jupyter Notebook 7.29.0, Tableau Public 2021.4

* Data Source: 201908-citibike-tripdata.csv, bikesharing.csv

## Results

Upon analysis of the bikesharing data, we were able to ascertain the following:

1. Number of rides
2. Trip duration
3. Checkout times
4. Weekday trips
5. Gender trips
6. User trips
7. Peak hours
8. Ending locations

### Number of Rides

<img src="https://github.com/crtallent/bikesharing/blob/main/Images/No.%20Rides.png"/>
As we can see from the above image, the total number of rides for August 2019 was 2,344,224.

<img src="https://github.com/crtallent/bikesharing/blob/main/Images/TripDuration.png"/>
The image above depicts the number of trips, filtered by the length of time that the bikes were checked out (trip duration).  Filters include trips lasting from less than one hour to 23 hours.  

<img src="https://github.com/crtallent/bikesharing/blob/main/Images/PeakHours.png"/>
The image above showcases the number of bike rides for each hour of the day, which highlights the peak hours.

<img src="https://github.com/crtallent/bikesharing/blob/main/Images/Checkout.png"/>
This image is similar to the trip duration data above, but allowing breakdown of users by gender.

<img src="https://github.com/crtallent/bikesharing/blob/main/Images/GenderTrips.png"/>
This data breaks down the number of rides by time and gender for each day of the week.

<img src="https://github.com/crtallent/bikesharing/blob/main/Images/WeekdayTrips.png"/>
This chart shows the number of trips per hour, per day of the week.

<img src="https://github.com/crtallent/bikesharing/blob/main/Images/UserTrips.png"/>
The above image shows a breakdown of user types, by gender, and by either customer or subscriber.

<img src="https://github.com/crtallent/bikesharing/blob/main/Images/EndingLoc.png"/>
Finally, this image shows a map of ending points, indicating the most popular checkout locations.

## Summary

As we can see from the data, bikesharing is popular in New York City.  With over 2,000,000 rides in the month of August alone, the data suggests that this is a useful commodity in the city.  By looking at the trip duration data, we can see that bikes are most often checked out for 4-5 hours, and that males check out bikes much more often than females. We can also see that between user types (customer and subscriber), the amount of bikes checked out to subscribers is much higher than those that do not have a subscription.  From the data, we can also see that bikes are checked out every day of the week, ahd that the peak hours for checkout times are daylight hours.  Finally, the data for the ending locations is useful, as it shows which locations patrons are most likely to return the bikes.

Further analysis will be necessary to determine whether bikesharing would be a profitable endeavor for Des Moines, as it is in New York City.  Additonal data would need to be analyzed, such as interest in bikesharing.  Income data would need to be analyzed as well, as well as the expenses for bike purchase and upkeep.  Another interesting angle would be to determine why so many more men utilize bikesharing services than women, and perhaps target the female population in advertisements if a bikesharing business is offered in Des Moines. 
