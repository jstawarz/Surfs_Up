# Surfs Up

## Overview of Analysis

In this analysis, we are working with W. Avy, a potential investor in our surf/ice cream shop venture in Hawaii. Before invensting in the venture,
W. Avy has requested that a weather analysis be performed in order to determine if Oahu is a suitable location for the store. Using SQLite, we will
retrieve weather data and descriptive statistics to demonstrate the typical weather in Oahu.

### Purpose

The purpose of this project is to supply W. Avy with additional weather analysis. W. Avy has requested further weather analysis be done 
for the months of June and December in an effort to see if the surf and ice cream shop buisness year-round. To accomplish this, we will use 
SQLite to pull the data and obtain the statistical elements.

## Hawaii Weather Results

### June Weather

Following the analysis, we generated the following table which offers some statistical insight into what typical June weather is like in Oahu. 

![This is an image](https://github.com/jstawarz/Surfs_Up/blob/main/Resources/june_statistics.png)

From this table we can determine

- The average temperature in June is 74.9 degrees
- The maximum temperature in June was 85 degrees
- The standard deviation is 3.25 degrees, which indicates that the temperature is consistently close to 75 degrees

### December Weather

Here, we generated the following table which offers some statistical insight into what typical December weather is like in Oahu. 

![This is an image](https://github.com/jstawarz/Surfs_Up/blob/main/Resources/december_statistics.png)

- The average temperature in December is 71.04 degrees
- The minimum temperature in December was 56 degrees
- The standard deviation is 3.75 degrees, which indicates that the temperature is consistently close to 71 degrees


## Summary of Results

Viewing the data analyzed we can demonstrate that weather in Hawaii is relatively pleasant year-round. Based on weather alone, a surf/ice cream
shop would likely perform well. We previously performed analysis to determine the amount of rainfall on the island over the course of the year. 
By refactoring our previous code, we can also determine the rainfall levels for June and December.  

![This is an image](https://github.com/jstawarz/Surfs_Up/blob/main/Resources/june_rain.png)
![This is an image](https://github.com/jstawarz/Surfs_Up/blob/main/Resources/december_rain.png)

By looking at the rain data, Oahu appears to be a fairly dry place the majority of the time. In June, 75% of the measurements taken were under
.12 inches of rainfall, whereas in December 75% of the measurements taken were under .15 inches of rainfall. Of note, both months have maximum
rainfall levels of 4.43 inches and 6.42 inches respectively. Considering the otherwise low amount of rainfall, this would indicate downpours that
occur sporadically. Taking rainfall into consideration as well as temperature, Oahu certainly seems to be a good location for the surf/ice cream shop.
