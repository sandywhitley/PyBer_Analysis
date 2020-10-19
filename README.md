# PyBer Challenge
VDAB mod 5 matplotlib
* By: Sandra Whitley
* October 2020
**************

## Overview
The purpose of this PyBer ride-share analysis is to provide ride, driver, and fare data visualizations based on city type (i.e. rural, suburbarn, and urban area). The first portion of the analysis combined PyBer city_data.csv and ride_data.csv (see links) data into a python dataframe (pyber_data_df) to glean total rides, total drivers, and total fares based on city type. Average fare by ride and by driver were calculated from this data. These calculations were organized into a summary table.

The second portion of the analysis referenced the same python dataframe (pyber_data_df) to calculate daily total fares by city type over a four month timeframe (1/1/2019 to 4/28/2019). The pandas matplotlib software was utilized to trend this data in a line graph.

![1. city_data.csv](/Resources/city_data.csv)
![2. ride_data.csv](/Resources/ride_data.csv)

## Results
As referenced in the PyBer Summary by City Type table, the law of supply and demand played out rather well. The more densely populated urban areas resulted in 68% of the total rides,  81% of the total drivers, 63% of the total fare revenue, and a 1.6 ride to driver ratio. This very competitive environment predictably resulted in the lowest fare by ride and by driver across the three city types. 

The least densely populated rural areas resulted in 5% of the total rides, 3% of the total drivers,  7% of the total fare revenue, and a .68 ride to driver ratio. This less competitve environment resulted in the an average fare per driver 235% higher and an average fare to ride 41% higher than the urban area.

The mid-density area resulted in 26% ot the total rides, 16% of the total drivers, 30% of the total fare revenue and a 1.28 rides to driver ratio. This environment resulted in an average fare per driver 138% higher and an average fare to ride 26% higher than the urban area.

The PyBer Total Fare by City Type Graph showed the total fare trends from 1/1/2019 to 4/28/2019. As noted above, the urban areas consistently yielded the highest total fare revenue, the rural areas yielded the lowest total revenue and and suburban areas yielded mid-range total fare revenues. This view demonstrated a very steep drop in urban and suburban total fares the last week of March then the subsequent recovery the first week of April. By the second week of April, the urban and suburban total fare trends returned to the pre-dip trends. The rural total fare trend did not exhibit the same dip.

![1. PyBer Summary Table(/analysis/PyBer_Summary_df.png)


![2. PyBer Total Fare by City Type Graph](/analysis/PyBer_fare_summary.png)

## Summary
Three recommendations gleaned from this data review:
* Although the PyBer Summary Table provides a cursory overview, it could have been enhanced with median and mode evaluation on the fare per driver and per ride. Additionally, a box and whisker plot would be a great visualization tool for this data.
* The urban and suburban total fare dip at the end of March and recovery at the beginning of April deserves further research and the lack of fluctuation in the rural total fares during this fluctuation also deserve greater understanding.
* As a customer-focused improvement, PyBer may want to consider recruiting more drivers in the rural areas to lower fares per ride.

