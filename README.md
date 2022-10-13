# PyBer Analysis

## Project Overview
Using Python, Pandas, and Matplotlib, 2 .csv files with ride-sharing data were merged and analyzed. A summary DataFrame was used to calculate and display the Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver for each type of city (urban, suburban, and rural). A multi-line graph was then created to display the total fares by city type each week from 1/1/2019 through 4/28/2019.

## Results

### Data Summary

The summary DataFrame shows that the number of total rides and total drivers in each city type increases as the population density increases from rural to suburban to urban. The total fares increases in the same way, but breaking down the average fare per ride and per driver shows an inverse relationship - the totals may be higher, but the amount earned per ride or driver is lower the more densely populated a city type is. 

<img width="823" alt="PyBer_summary_df" src="https://user-images.githubusercontent.com/111674383/195530037-b434a66e-529c-4180-92c0-6a25776c6308.png">

### Multi-line Graph

The multi-line graph helps visualize the data trend for total fares by city type over a 4 month period. With the exception of mid-February through mid-March, when the total fares in each city type have corresponding rises and falls, the total amount earned in each city type doesn't appear to correlate.

![PyBer_fare_summary](https://user-images.githubusercontent.com/111674383/195526799-6c1f7710-cab2-4c0c-b81b-326ab63091ae.png)

## Summary

Based on these results, the following recommendations should be considered.

1. Assess the needs of customers in rural and suburban cities. The average fare per ride is higher in these areas (presumably, the less densely populated an area is the longer the rides last, leading to increased total fares). If the customer demand would support an increase in drivers, assuming the average fare per ride stayed the same, the company would see an increase in total fares.
2. Evaluate flexible charging plans. Assuming that customers are currently charged the same way and at the same rates across the board, even small price increases across city types during times of historical highs (e.g., late Februrary) would lead to increased revenue. 
3. Improve access to ride-sharing in rural and suburban cities. Increases in advertising budgets or community outreach through partnerships with local hotels, conference centers, restaurants, and bars could drive the number of rides in those city types higher. 
