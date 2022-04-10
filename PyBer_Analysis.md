# PyBer_Analysis
## Overview
The purpose of this analysis is to explain how the type of city (rural, suburban, or urban) affects the price of the fare for the ride. This relationship is important to understand because it impacts both the driver and rider. Riders prefer to pay lower fares, while drivers want to ensure they are being adequately compensated for their work. Looking at this data can help us determine if there are gaps or inconsistencies in this relationship that need to be addressed.
A data frame was constructed using two csv files showing the rideshare data for specific cities, and the data for individual rides. They were combined using a common detail (the name of the city) to create one unified data frame. From there, we extracted the total rides, total drivers, total fares, average ride fare, and average driver fare for each city type. 

## Results

### The percentage of total rides by city type
More than 2/3 of the total rides in 2019 were realized in urban cities. Suburban areas count for over 26% of the total rides and rural cities have the smallest proportion with only for 5.3%.

<img width="468" alt="Fig 2" src="https://user-images.githubusercontent.com/100812308/162627109-4667a17f-f4eb-4c71-b3a5-4a3d5711455f.png">


### The percentage of total drivers by city type
Urban cities drivers were by far in majority with 80.9% of the company's drivers force in 2019. Surbuban and rural drivers were respectively 16.5% and 2.6% of the total drivers in 2019.

<img width="476" alt="Fig 3" src="https://user-images.githubusercontent.com/100812308/162627127-040c56ef-1742-4d38-8a5d-7a01cac9d365.png">


### The percentage of total fares by city type
Here again we notice the influence of urban areas in the company's business model. Close to 63% of the 2019 total fares was realized in urban cities. Surbuban activity counted for about 31% and the smallest proportion was in rural neighborhoods.

<img width="496" alt="Fig 4" src="https://user-images.githubusercontent.com/100812308/162627128-c427d7cb-b209-4d9e-aadd-1db441622e11.png">


### The average fare per ride and driver by city type
The following bubble chart shows the relationship between the average fare price and the number of rides and drivers categorized by the different city types.

We notice that the average fare tends to decrease as the total number of rides per city increases. This is a negative relationship.
As per the driver count per city, it appears that the bubbles get larger when the average fare decreases and/or when the total number of rides increases.
Rural areas have the least number of drivers and rides per city and its fare ranges from high to middle prices. It is difficult to see the relation between those parameters. 

<img width="803" alt="Fig 1" src="https://user-images.githubusercontent.com/100812308/162627142-7d281646-a831-42a4-a178-befccba845f1.png">

### The total fare by city type
The following line chart shows the total fare by city type from January to April 2019.

The total fare by city type (see above line chart) has one instance where there is an increase in total fare, followed by a decrease, for all 3 city types. There is an increase in the middle of February, and then a decrease at the start of March. This is the only point across the four months where there is a trend shared by all 3 city types.

<img width="832" alt="Pyber_fare_summary" src="https://user-images.githubusercontent.com/100812308/162627214-b8f7acd4-cb63-4535-a332-190327702f0b.png">

## Summary

- In the most underserved neighborhoods, PyBer ride-sharing services would not be the first option for travels as the fares are pretty high.
- The correlation between the drivers force, the number of rides and the average fare price is not clear so additional analysis including geographic size, travel distances, cellphone coverage would be needed to get a clearer picture.
- Suburban drivers were only about 17% of the total drivers but accounted for more than 30% of the total fares and just above a quarter of the rides.
Improving access to PyBer service in those areas will imply finding the right balance between incentives for more riders to join in and the right fare charge that will motivate riders to pick PyBer app as the first choice for their travels.
Additional analysis including geographic size, population and social conditions, travel distances will be of help to understand the correlation better. 
- The general tendencies is high number of drivers and rides goes with medium to low fare.
We notice some urban cities with low number of drivers and low average fare but pretty high count of rides. Analyzing the average number of drivers against the population and infrastructure and economic activity in those cities would help understand those disparities.
