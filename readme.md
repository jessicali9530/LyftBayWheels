# Exploring the San Francisco Bay Wheels Bikesharing Data
## by Jessica Li


## Dataset

The [2017 Bay Wheels Bikesharing Data](https://www.lyft.com/bikes/bay-wheels/system-data) 
provided by Lyft contains anonymized trip information for over 500,000 bike rides this year. 
[Bay Wheels](https://blog.lyft.com/posts/introducing-bay-wheels-new-bikes-and-a-new-name) is 
the latest hybrid e-bike offering by Lyft to get around the San Francisco Bay Area on two wheels. 
The program officially started on June 28, 2017. There are currently over 2,600 bicycles in 262 
stations across San Francisco, East Bay and San Jose. Bay Wheels, like other bike share systems, 
consists of a fleet of specially designed, sturdy and durable bikes that are locked into a network 
of docking stations throughout the city. The bikes can be unlocked from one station and returned 
to any other station in the system, making them ideal for one-way trips. The bikes are available 
for use 24 hours/day, 7 days/week, 365 days/year and riders have access to all bikes in the network 
when they become a member or purchase a pass. In this exploratory data analysis, we look at how 
the bikesharing program fared from June 28 to December 31 of 2017, the first 6 months after this 
program was established. 


## Summary of Findings

In the exploration, we found that a large part of the behavioural use and demographic user base 
of Bay Wheels is associated with the working adult group in San Francisco. A couple key insights lead
to this observations. For one, bikeshare trip durations are mostly very short, with a median of only 
10 minutes. The mean age of the user base is 38 and hovers mainly around the age range of 30-35. 
77% of the user base is male. About 11% of the user base is part of the subscription model, yet
subscribers roughly take 5-6 times more rides than customers. Bike rides are also much more frequent
during weekdays as opposed to weekends, with two spikes around the beginning and end of a regular 9am-5pm 
working day. These findings all point to a trend that most users using Bay Wheels are working age males
that consistently ride short rides presumably for their daily commute. A closer look into bivariate and
multivariate visualizations with user type against multiple other variables revealed that the subscriber
group appaers to comprise mostly of this working adult demographic, while the customer group appears
to capture a wider demographic including tourists and non-working people.


Outside of the main variables of interest, I also observed that bikesharing in San Francisco overall
is a very successful mode of transportation around the city given its uniquely dense composition. 
Bikesharing is used much more for convenient transportatino and less for sports and tourism here.

## Key Insights for Presentation

For the presentation, I focused primarily on the gender makeup of the Bay Wheels program and
how that can be crossed with user type information to reveal the rather prevalent trend of the
dominany male technology industry in San Fransisco. I start by sharing a pie chart that visualizes
the 4:1 male to female ratio in the program overall. My second visualization is a two-bar 
subplot that reveals the difference in hourly bike usage by user type, suggesting a relationship
between the subscriber group and the San Francisco working adult group. Finally, my third chart
pulls together the gender and user type trend to reveal that the subscriber group has a 5:1
male-to-female ratio whereas the customer group has a 3:1 male-to-female ratio, attempting to 
draw an observation that the subscriber group is representative of the dominant male technology
industry that concerns San Francisco today.