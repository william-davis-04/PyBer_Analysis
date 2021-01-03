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

![Summary](PyBer_Analysis\Challenge_Images\Pyber_Summary_DF.png)

## Challenges Overcome
Stackoverflow was a tremendous resource for this project. The dates used were initially interpreted as a string, so a date time function was used to convert them from string to date-time. This allowed the values to be used with matplotlib to create a graph over a selected time period. The data read in from the csv file did not require any clean up. This may not always be the case and it is important to look over the csv file before beginning any analysis. 

## Take away thoughts
Based on this data, the CEO of PyBer may want to reconsider spreading the ride sharing service to rural areas. Rural rides make up a small percentage of users, but they are the most expensive ride type. This most likely has to do with the fact that less people are using ride sharing services in rural areas, and a lack of demand for ride sharing services in rural areas. Additional analysis could be done with the ride ID’s to discover how many rides per day each driver was completing. A further analysis of the date-time values could also provide more insights such as which days of the week are most popular to use PyBer. This could allow the CEO to get more drivers on the road during busy times. Urban and suburban areas make up the core of the business and they should be focused on more heavily than rural areas.  


![Total Fares By City Type](Fig8.png)

Yellow Line = Urban Cities

Red Line = Suburban Cities

Blue Line = Rural Cities

![Summary DataFrame](PyBer_dataframe.png)