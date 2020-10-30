# PyBer_Analysis

## Overview of Project

The CEO wants me to create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. Finally, I’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Resources

-	Data Source: city_data.csv, ride_data.csv
-	Software Used: Python 3.7.6, Jupyter Notebook
## Results

![PyBer Summary](https://github.com/chreroax1/PyBer_Analysis/blob/main/Resources/Pyber_summary.png)

Looking at city type, the total rides, total drivers and total fares is greatest in urban cities and least in rural cities. However, the average fare per ride is greatest in rural cities at $34.62, with suburban cities at $30.97, but for urban cities is only $24.53. Also, because the number of drivers is so large in urban cities, the average fare per driver is much lower ($16.57) than in rural cities ($55.49).

![PyBer Chart]( https://github.com/chreroax1/PyBer_Analysis/blob/main/Resources/Pyber_chart.png)

Looking at the sum of the fares by city type over time, we can see that the total fares in urban cities is much greater than in either suburban or rural cities.
-	The line plot for urban cities often shows an average fare more than four times that of the rural cities, sometimes five times greater.
-	Both the suburban and rural cities saw a peak in total fares at the end of February.
-	The highest sum for rural cities was in early April 2019.
-	The highest sum for suburban and urban cities was at the end of February 2019.
-	Suburban fares seemed to increase through January but then taper off until the last week in February.
-	Urban fares increased through the end of February and then became intermittent through March.

While the total fares are much lower in rural cities, the stability shown in the line plot and the average fare per ride and per driver shows that having drivers in rural cities is profitable. The total fares in urban cities make up for the lower averages per ride and per driver.

## Summary 
Based on the data shown in the PyBer summary and Fare vs Date plot we can come up with the following recommendations:

- 	The fares from rural area are pretty consistent throughout the year but the number of rides is not that much. This means that the demand of rides is less in rural area. There could be more potential in rural area if the pricing model can be revised.
-	If we look at the Fare vs Date plot for each city type, it is observed that the fares are peaking towards the end of Feb in all three city types. This means that the demand is higher during that time. The average fare per driver can be reduced in suburban and rural areas to see if a greater number of drivers become available during that time which in turn will give more room to the number of rides and ultimately will increase the total fare.
-	The company can look into starting PyBer Eats as a food order and delivery platform which will open other avenues of generating business specially in the urban area.

