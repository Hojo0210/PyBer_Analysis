# PyBer_Analysis

## Overview
Using a dataset from the city_data.csv and the ride_data.csv, a new dataframe was made to show the total rides, drivers, and fare amount, as well as the average fare and average fare per driver. This dataframe was then used to make an additional dataframe to show the sum of the fares for a given range of dates. The range used was 2019-01-01 to 2019-04-28, but this code could be refactored for any date that we have data for. This was then pivoted to show the total fare for each city type, on a weekly basis. This final dataframe was used to create a line chart to show the total fares by city type across the given date range.

## Results
After finishing this analysis, it is highly apparent that urban cities have the highest volume out of all city types. The total rides, drviers, and fares were significantly higher than in suburban or rural cities. However, the average fare and the average fare per driver were lower than the other two city types. Rural citys had less than a tenth of the amount of rides in urban cities. There were also more than thirty times more drivers in urban cities. The total fare was also significantly less, barely ten percent of the fare value of urban cities. That being said, the average fare and fare per driver was much higher than both urban and suburban cities. 
![Alt Text](https://github.com/Hojo0210/PyBer_Analysis/blob/main/analysis/pyber_summary.png)

The line chart clearly shows all of this data, and also shows the value of the fares across a given date range. 
![Alt text](https://github.com/Hojo0210/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary
