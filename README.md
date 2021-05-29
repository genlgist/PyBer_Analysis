# PyBer_Analysis

Regina Negrycz 
genglist@yahoo.com 
Module 5 Challenge 
Submitted 29 May 2021 
Due 30 May 2021 
https://github.com/genlgist/PyBer_Analysis/blob/main/Resources/city_data.csv
https://github.com/genlgist/PyBer_Analysis/blob/main/Resources/ride_data.csv
https://github.com/genlgist/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png
README.md

# Overview of the PyBer Analysis

I needed to use the Pandas groupby() function with the count() and sum() methods on the PyBer DataFrame columns in order to get the total number of rides, total number of drivers, and the total fares for each city type. I next needed to calculate the average fare per ride and the average fare per driver for each city type. The data I gathered had to be added to a new DataFrame and subsequently formatted.

# Results

The Urban city type had the highest total rides, drivers and total fares.  This resulted in the lowest average fare per ride per city type and the lowest average fare per driver per city type.  The Rural city type had the lowest total rides, drivers and total fares.  This resulted in the highest average fare per ride per city type and the highest average fare per driver per city type.  The Suburban city type was in the middle for rides, drivers and fares as well as the average fares per ride and driver.

	Total Rides	Total Drivers	Total Fares	Average Fare per Ride	Average Fare per Driver
Rural		125	78		$4,327.93	$34.62			$55.49
Suburban	625	490		$19,356.33	$30.97			$39.50
Urban		1,625	2,405		$39,854.38	$24.53			$16.57
 
In analyzing the weekly summary for January to April, rural city types had the least amount of fares, whereas suburban and urban types appeared to have rotated, one having fares one week and the other having fares the next week.

type	Rural	Suburban	Urban
date			
2019-01-01 00:08:16	NaN	NaN	37.91
2019-01-01 00:46:46	NaN	47.74	NaN
2019-01-01 02:07:24	NaN	24.07	NaN
2019-01-01 03:46:50	NaN	NaN	7.57
2019-01-01 05:23:21	NaN	NaN	10.75
2019-01-01 09:45:36	43.69	NaN	NaN
2019-01-01 12:32:48	NaN	25.56	NaN
2019-01-01 14:40:14	NaN	NaN	5.42
2019-01-01 14:42:25	NaN	NaN	12.31
2019-01-01 14:52:06	NaN	31.15	NaN
2019-01-01 17:22:58	NaN	NaN	42.11
2019-01-01 21:04:01	NaN	NaN	11.71
2019-01-02 00:13:08	NaN	44.71	NaN
2019-01-02 00:44:03	NaN	NaN	43.72
2019-01-02 00:56:53	NaN	NaN	37.34
2019-01-02 01:41:26	NaN	49.95	NaN
2019-01-02 01:46:40	NaN	NaN	34.79
2019-01-02 06:55:36	NaN	NaN	16.96
2019-01-02 07:26:53	NaN	33.57	NaN
2019-01-02 09:28:27	NaN	NaN	19.81
 
The graph showed that there was a spike in the fares of all city types in the last week of February.  The fares were the least expensive in the rural areas and the most expensive in the urban areas, more than likely due to increased congestion.

The graph also showed April was inconsistent for suburban city types while urban types dropped slightly and rural types continued to decline.   

 

# Summary

The Summary df shows that the average fare per driver is much higher in rural cities than in urban cities, more than likely due to the fact that there are more drivers in the urban areas.

Recommendations:

1.	In the urban areas, total number of drivers is greater than the total number of rides.  This should be investigated to determine why there are so many drivers.  Does one city have significantly more than the other cities?  Or one area of cities significantly more than another area of cities? 
2.	Public events per each city type should be analyzed to determine what parking is available and types of mass transportation are available.  If there’s sufficient number of both, this would warrant fewer drivers in those areas during those events.  Each city type should also be analyzed for major construction projects which could impact the cost of the rides.
3.	The data captured should be augmented to include the length of time and miles per ride.   This could help indicate periods of congestion due to public events or major construction projects. 
