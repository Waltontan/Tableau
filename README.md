# Tableau Homework - Citi Bike Analytics

## Background

The data for this analysis is obtained from the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

Due to the limitation of Tableau Public only the months from August 2021 till the end of Dec 2021 have been analysed.

This has incorporated 13.3 million instances of rental as the dataset.

## Analysis

**Ride Statistics**
* There are peak usage at 8am and 5pm.
* There is likelihood that these correlates with the time to get to work and finishing work.
* 80% of the trips are completed under 20mins
* 80% of the count of distances are completed under 2.8km

**Count of Member vs Non-Member**

* It can be seen that the count of bike rental has dropped since Aug.
* The percentage of users who are members actually increase despite the drop in total count.

**Ride Deep Dive**

* This dashboard was created for giving the user the ability to deep dive into the data.
* For example, if a start station is chosen. The first observable trend is the end station map showing the most common trip/end point for someone starting from that station.
* The histogram will then show the distribution of trip duration and distance that are typical of that start station.
* This data will be useful for prioritising of the maintenance regime for the bikes.
* If an end station is subsequently selected. The histogram will then show the distribution of the time taken to travel between the 2 stations.
* This can indicate the frequency of bikes between the popular stations and provide an idea of how many bike should be providede at that station.

**Permanent Rental**

* This dashboard provide an idea of the pockets of station where the bikes have been rented for a period of more than 12 hours.
* One example is a ride which lasted for 253 hours and only travelled 1km.
* This shows that there is a possibility of a bike being rented out "permanently". This is where a person might have checked out a bike once and keeping it for their own use for an extended period of time before returning. 
* Often there might be a reason for returning it and there maybe a possibility that there is some faults with the bikes. Hence this can also highlight that at these locations there may be bikes that require maintenance. 

## Considerations

These current data set is able to give some insights into the usage habits and possible area where maintenance is required. 

With a bigger data set with the same data there is the possibliity to line the usage with different seasons/events around New York city.

If there were to be more membership data and maintenance cost data. This analysis can be extended further to ascertain whether the citibike program is profitable. 
In addition, there can also be the possibility of diving deeper into usage habits to create marketing campaigns that'll attract more users or increase membership counts. 