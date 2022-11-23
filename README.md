# PyBer_Analysis
 Module 5: PyBer with Matplotlib

## [Overview of the Project](https://courses.bootcampspot.com/courses/2523/assignments/43090?module_item_id=806188)

For this project the goal was to show total weekly fares for each city type. We wanted to explore how data differs by city type and if we can infer any insight into affordability for various cityscapes. 

Our source data is found in the Resource folder: [city_data.csv](https://github.com/ahualoh/PyBer_Analysis/blob/main/Resources/city_data.csv) contains rows of  the city name, the number of drivers in that city, and the type of city (Rural, Urban, Suburban); [ride_data.csv](https://github.com/ahualoh/PyBer_Analysis/blob/main/Resources/ride_data.csv) contains rows of info for each ride taken - the city, date, fare for the ride, and the individual ride id. Each data set is from January to early May of 2019.

## Results 

For general reference of all the data given, see table "[Challenge_Summary_All_Data](https://github.com/ahualoh/PyBer_Analysis/blob/main/Analysis/Challenge_Summary_All_Data.png)". There were a total of 2,375 rides between January and March 2019, where the avereage ride fare was $26.75. Fares ranged from $4.05 to $58.56. 

The two data sets were merged in to one table "[Challenge_Summary_by_City](https://github.com/ahualoh/PyBer_Analysis/blob/main/Analysis/Challenge_Summary_by_City.png)", which aggregated  total rides, total drivers, average fare per ride & driver, and total fare by city type.

(It should be noted that Average fare per driver is NOT what each driver received, but how ride fares (cost) vary on the driver pool for each city type.) 

We can see that that most rides were taken in Urban cities (more than 50% of the 2375 rided we analyzed), and the least was in Rural cities (less than 5%). Driver counts (2973 total) for each city type differ more, with about 80% of drivers being in Urban cities, and less than 2% of drivers in Rural cities. Average fares per ride are inverse, with the greatest fare in Rural, and the lesser fares in Urban cities. 

As we can see in "[Challenge_fare_summary](https://github.com/ahualoh/PyBer_Analysis/blob/main/Analysis/Challenge_fare_summary.png)" There are no dramatic swings in fares in the period we analyzed within each city type's trendlines, but you can see the stark difference in the fares between city types. In general, fares increased steadily through the entire analyzed time period, with a overal spike starting around late February and a platue as we approach March. 

## Summary

There are not many solid conclusions or decisions we can make with the results from this summary alone. But the results do lead us to ask more questions that will help us continue exploring. Some of key takeaways...

1 - driver counts in each city. As stated above, there is a greater disparity in driver count per city type compared to how many rides are taken in each city type. Each driver in Rural cities is on average, making more than 3 times per rise than Urban drivers. Changing the amount of drivers available in rural communities may influence the availability and accessibility (cost-wise) to rural riders. This begs the question of whether more drivers are willing to drive in rural cities. 

2 - We might want to find more information on the demongraphic of each city type, and additional ride info, such as time and distance of rides, what purposes the rides are for, how many (general) people seem to be on rides... etc. A hypothesis is that rural rides could potentially cost more because they have to travel longer distances in general (in addition to the scarcity of supply).  

3 - Are the city type of rides based on their starting point, ending point, or both? This loosely ties both the above two points together... because this might change if data is being correctly framed, it could influence how many drivers are willing to driver in respective city types, and could help us determine what kinda of demand there are based on city type. 

Onward to finding out more info! 