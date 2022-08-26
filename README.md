# PyBer_Analysis

## Overview
V. Isualize has given myself and Omar a brand-new assignment. We were taked to create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, we were to then create a multiple-line graph that shows the total weekly fares for each city type. Finally, we will then summarize how the data differs by city type and how those differences can be used by decision-makers at PyBer. Now that we have orgianized, formatted, and visualized the data, we can begin now share the results of the work we have done. 

## Results

The '.groupby' function was extremely helpful in our analysis. We were able to split the data of Drivers, Fares, and Rides by the type of city. With that information pulled we were able to then see what the average fare per ride and average fare per driver would be based on each city type. This gave us a good idea of what we could expect to see in the eventual graph we will be creating. 

### Data by City Type
![City by Type Data](https://github.com/Andrew-E-Walters/PyBer_Analysis/blob/main/analysis/Pyber_Summary.png)

Some intresting take aways are the Total Rides, Total Drivers, and Total Fares are Highest in Urban Citys, and are lowest in Rural Cities. However The Average Fare per Ride is highest in the Rural areas and lowest in the Urban areas. While we cant definitively say, we could infer that avalibilty of drivers could have a corelation with the price of a ride. We also were tasked to create a multiple line plot that shows the total weekly of the fares for each type of city. First step was getting the data seperated into each city type, then we had to set the data to datetime so we could look at it from a weekly perspective. 

### Weekly Data 
![Weekly Data](https://github.com/Andrew-E-Walters/PyBer_Analysis/blob/main/analysis/Weekly%20Data.png)

From our ealier analyis we know that we can expect to see some differences in the data based on city type. 

### Total Weekly Fares for each type of city
![Weekly Graph](https://github.com/Andrew-E-Walters/PyBer_Analysis/blob/main/analysis/Pyber_Summary.png)

We can see a distinct difference in each city type. The easiest to see is that there is a clear diffrence in totals of each fare for each city type. Urban has the highest total fares and Rural has the lowest fares. While this does show a good breakdown of how the cities differ in total fares I do have some recomendations. 

## Summary
My recomendations:
- A more accurate way to look at the business might be to look at each city type by average fare cost per week. This could let us know if there are weeks where people are willing to spend more. Are there weeks where Rural areas are cheaper than Suburban or Urban? 
- A breakdown of what the number of rides per week by city type. This will let us know if there are weeks that each city type is in need of a driver. There are more Urban drivers than the other city types, but are there any weeks where that isnt the case?  
- We do not have this data on hand, but if we could gather how many drivers are available by week then we could conduct analysis on if the number of rides and cost of fares have anything to do with the relative availibilty of drivers. Are the weeks with more drivers leading to a drop in price of the ride? 


