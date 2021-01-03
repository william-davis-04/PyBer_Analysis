# PyBer_Analysis

## Resources 
data source: ride_data.csv, city_data.csv

software: jupyter notebook, python, visual studio code 


##  Overview
The purpose of this project is to create a DataFrame that summariezes some of the key metrics of the ride-sharing data, then document the results in writing to include charts that visualize the results.  challenges you encountered and overcame, and any future recommendations for analysis. The ride-share data analyzed provided a general view of the simularities and differences in data when comparing and contrasting urban, suburbuan and rural routes. The data catagories analyzed include: 

- Total Rides
- Fares
- Number of drivers 
- Average Fare per ride 
- Average Fare per Driver  

These categories are organized and by area i.e. (Urban, Suburban, Rual) and displayed in the summary table for comparison.

![Summary](https://github.com/william-davis-04/PyBer_Analysis/blob/main/Screenshot%202021-01-03%20134830.jpg?raw=true)

In addition to the summary table above, a multiple line plot was created to show the sum of the fares for each city type by month.  This chart provided a great visual analysis of the relationship between the total fares and the time of year (months) for each of the city types (Urban, Suburban, Rual). On clear visual cue from the chart is the sharp increase in total fares between February and March which is common among each city type.  Also of note is the increase in total fares in suburban areas in the month of May, which differs from suburban and rural city types. See the chart below for a visual.  

![PltMap](https://github.com/william-davis-04/PyBer_Analysis/blob/main/pyber_pltmap.png)

Yellow Line = Urban Cities

Red Line = Suburban Cities

Blue Line = Rural Cities

## Challenges 

There were some slight challenges that occured with creating the plot chart above. The steps required included merging the existing dataframes, reorganizing some of the information and grouping data. Creating a new DataFrame, then converting this DataFrame into a Pivot table. Then ulitmately creating a brand new DataFrame with this approach and plotting it using the object-oriented interface method.  My challeges main occured when creating a pivot table from the the Pandas DataFrame and utilizing the 'loc' attribute.  I overcame this challenge by re-familiarizing myself with this attribute during my course training as well as referencing tutirials on stackoverflow and online.

Based on this data, the CEO of PyBer may want to reconsider spreading the ride sharing service to rural areas. Rural rides make up a small percentage of users, but they are the most expensive ride type. This most likely has to do with the fact that less people are using ride sharing services in rural areas, and a lack of demand for ride sharing services in rural areas. Additional analysis could be done with the ride ID’s to discover how many rides per day each driver was completing. A further analysis of the date-time values could also provide more insights such as which days of the week are most popular to use PyBer. This could allow the CEO to get more drivers on the road during busy times. Urban and suburban areas make up the core of the business and they should be focused on more heavily than rural areas.  

##  Reccomendations 

Pyber may want to consider analyzing the average fair by date and compare this against the total fairs.  This would enable the company to take a deeper look into the proper pricing struction to captialize their revenue.  This could be created by not summing the values but instead taking an average when creating a new DataFrame from the pivot table.  Another reccomendation is to consider is that amount of total drivers by month to identify areas to capitilize on demand.  This could be achieved by plotting the chart by driver count and date for each city type. 

