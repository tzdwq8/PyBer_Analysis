# PyBer Analysis

## Project Overview
The purpose of this project is to assist the ride sharing app company, PyBer, in analyzing data to improve access to ride sharing services and determine affordability for underserved neighborhoods.  To accomplish this task we analyzed data such as city/city type, number of drivers, number of rides, and fare amounts.  The completed output summarizes data to improve performance by city type.

Deliverables include:
- Creation and merging of applicable DataFrames.
- Creation of bubble charts visualizing relationship amongst data types. 
- Determining mean, medium, and mode of data types.
- Determination of possible outliers.
- Creation of line chart to determine trends.  

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Jupyter notebook 6.1.4, Python 3.8.5

## Results
The below DataFrame illustrates the differences between city types:

![DataFrame](https://user-images.githubusercontent.com/85590155/126083405-3f3dd7c5-5c11-43b3-b44e-91cfcca56474.PNG)

As expected, the more dense the city type, the greater amount of total rides.  This is likely due to a greater population of available riders.  Also, with a greater population of riders, there are a larger amount of drivers which generates more total fares in the more dense city types.  However, there is an inverse relationship regarding fares.  As the city type becomes less dense, the average fare increases.  This is likely due to greater distance traveled per trip.

----------

The below line chart illustrates the total fare by city type from 1/1/19 to 4/29/19:

![Chart](https://user-images.githubusercontent.com/85590155/126083652-3e371be7-082e-4104-94b2-74a26f026b6d.PNG)

All three city types seem to follow the same trend, in which fares peak at the end of February and the beginning of April.  The one difference being Suburban fares continue to rise throughout the month of April.  Having said that all city types are experiencing more fares at the end of the time period than the beginning.  This could be due to increase activity as the weather becomes warmer, or greater awareness of service over time.

## Summary
The Urban areas have more total drivers than total rides over the given time period, while the Suburban and Rural areas have less total drivers than total rides.  In conjunction, the Urban areas are the only areas where the average fare per driver is less than the average fare per ride.  This points to an oversaturation of drivers in the Urban areas, and profitability could be improved by a reduction of Urban drivers.

The Rural areas have the highest rides per driver ratio of all the city types.  This points to the Rural areas potentially being underserved.  While placing more drivers in the rural areas could lead to a reduction in average fares, total fares could rise.  This would be due to an increase ride volume due to an increase driver availabilty and a decrease in fares.

During the month of April, total fares in the Suburban areas have spiked.  This could be due to a combination of pricing and ride volume.  An investigation to understand the root cause would be beneficial to determine if more drivers are needed if this growth trend is expected to continue.
