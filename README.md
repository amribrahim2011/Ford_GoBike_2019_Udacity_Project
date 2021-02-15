# (Communicate Data Findings: 2019 Ford Go-Bike Project)
## by (Amr Ibrahim (amr.ibrahim2011@gmail.com))


## Dataset

> Ford GoBike, the San Francisco Bay Area’s new regional bike share network, is a public-private partnership between the Metropolitan Transportation Commission and Motivate. Motivate, the global leader in bike share, operates tens of thousands of bikes across four continents. Ford Motor Company is the program’s title partner, whose support enables Ford GoBike to bring the myriad public benefits of state-of-the-art bike share to San Francisco, San Jose, Oakland, Berkeley and Emeryville — at no cost to taxpayers for capital or operational expenditures

> This document explores the Ford GoBike's trip data for Feb-2019. The attributes included the trip start/end time, as well as additional measurements such as user type, gender, and age. The dataset initially contained 183K observations but 9K data points were removed from the analysis due to missing values in some fields, data inconsistent, or outliner issues.

> This project is divided into two major parts. In the first part, we will conduct an exploratory data analysis on a dataset Ford GoBike System Data. We will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part should be structured, going from simple univariate relationships up through multivariate relationships. 

> In the second part, we will take my main findings from my exploration and convey them to others through an explanatory analysis. To this end, I will create a slide deck that leverages polished, explanatory visualizations to communicate my results.




## Summary of Findings
1. Regarding Trip Duration
1.1) Trip Duration is so dependable on the age of the member, when the age at the range of 20 to 45, the trip duration is higher than the older ages.
1.2) For the age, duration, and user type, both Customer and Subscriber are showing similar trends for age and trip duration, but for subscribers the trip duration is higher for older age.


2. Regarding the bike ride trends and biker types:
2.1) Tuesday, 5:00 PM has the highest biker counts across 7 days, 24 hours.
2.2) 5:00 PM has the most male bikers compared to other hours. 8:00 AM and 5:00 PM have more female bikers compared to other hours.
2.3) 5:00 PM has the most 'Subscriber' bikers compared to other hours. It also has the most 'Customer' bikers compared to other hours.
2.4) Tuesday has the most male bikers compared to other days. It also has the most female bikers compared to other days.
2.5) Tuesday has the most 'Subscriber' bikers compared to other days. Saturday has the most 'Customer' bikers compared to other days.





## Key Insights for Presentation

>Below are the insights for the presentation:
> 1) the distribution of biking durations is skewed. After log transformation and outliner removing, we may visualize and interpret data better.
> 2) Peak biking day and time are shared. Biker types were analyzed.
> 3) the patterns/trends for bikers from different age group are shared.
> 4) In the case of age, the distribution is more concentrated between 20 to 40 years old.
