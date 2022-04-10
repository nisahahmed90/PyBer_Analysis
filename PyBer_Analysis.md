# PyBer_Analysis
## Overview
The purpose of this analysis is to explain how the type of city (rural, suburban, or urban) affects the price of the fare for the ride. This relationship is important to understand because it impacts both the driver and rider. Riders prefer to pay lower fares, while drivers want to ensure they are being adequately compensated for their work. Looking at this data can help us determine if there are gaps or inconsistencies in this relationship that need to be addressed.
A data frame was constructed using two csv files showing the rideshare data for specific cities, and the data for individual rides. They were combined using a common detail (the name of the city) to create one unified data frame. From there, we extracted the total rides, total drivers, total fares, average ride fare, and average driver fare for each city type. 

## Results

### The percentage of total rides by city type
More than 2/3 of the total rides in 2019 were realized in urban cities. Suburban areas count for over 26% of the total rides and rural cities have the smallest proportion with only for 5.3%.

![Fig2](https://user-images.githubusercontent.com/100812308/162626637-8e27dd6b-2b8c-4ded-acab-8ac7fb4d897f.png)

### The percentage of total drivers by city type
Urban cities drivers were by far in majority with 80.9% of the company's drivers force in 2019. Surbuban and rural drivers were respectively 16.5% and 2.6% of the total drivers in 2019.

![Fig3](https://user-images.githubusercontent.com/100812308/162626665-bec33f7c-2962-46e4-a68d-1b62e4ddc404.png)

### The percentage of total fares by city type
Here again we notice the influence of urban areas in the company's business model. Close to 63% of the 2019 total fares was realized in urban cities. Surbuban activity counted for about 31% and the smallest proportion was in rural neighborhoods.

![Fig4](https://user-images.githubusercontent.com/100812308/162626718-3c3efccf-9a5a-40d0-931f-991a023f5ac1.png)

### The average fare per ride and driver by city type
The following bubble chart shows the relationship between the average fare price and the number of rides and drivers categorized by the different city types.

We notice that the average fare tends to decrease as the total number of rides per city increases. This is a negative relationship.
As per the driver count per city, it appears that the bubbles get larger when the average fare decreases and/or when the total number of rides increases.
Rural areas have the least number of drivers and rides per city and its fare ranges from high to middle prices. It is difficult to see the relation between those parameters. 

![Fig1](https://user-images.githubusercontent.com/100812308/162626797-abf88707-51f7-4980-b6d0-499559e4b06f.png)

### The total fare by city type
The following line chart shows the total fare by city type from January to April 2019.

![PyBer_fare_summary](https://user-images.githubusercontent.com/100812308/162626844-701c4583-f252-4dd6-a08a-0be68bbf8ef8.png)
