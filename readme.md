# Diamonds Data Exploration

## Dataset

The data consisted of duration and attributes of approximately 183,412 trips in 
San Francisco Bay Area, California. The attributes included the distance, member 
age, start day of the week, start hour, type of user, and gender. There were some 
quality and tidiness issues in the dataset and they were fixed. Also, there were 
some outliers related to duration, distance, and member age discovered during the 
exploratory phase and they were removed from the dataset to safety reasons.


## Summary of Findings

In the exploration, I found that there was a positive relationship between the
trip duration and its distance, with modifying effects from the user type,
member age, member gender, start day of week and start hour given to the trip. 
The relationship is approximately linear between duration and distance. 
I found that all the trips in the dataset were made in February. The day of the 
week with the most amount of trips is Thursday. There are two peaks of usages 
at 8am and at 5pm. Duration has a long-tailed distribution, with a lot of trips 
on the low duration end, and few on the high duration end. When plotted on a 
log-scale, the duration distribution looks unimodal, with the highest peak 
around 10 minutes. The distribution of trip distance is right skewed and it has 
unimodal shape, being the most frequent distance between 1 and 2 kilometers.
The distribution of member age is right skewed and it has unimodal shape. The 
most frequent range of member age is between 25 and 45 years old. The majority 
of the users are subscribers around 90%, only 10% are customers. Around 75% of 
the users are male, following by 24% of females. Only less than 1% are set as 
other gender. Subscriber's trips are shorter in terms of duration and distance 
than the customer's trips. While subscribers use the service mainly for 
commuting to work (mainly weekdays and the peak hours are from 7am till 9am and 
from 4pm till 6pm), customers use the service across the full week. Some of the 
customers use the service for commuting as well but others for leisure reasons.
Customer's trips have a higher duration over the weekends, while subscriber's ones
remains mainly consistent over weekdays.


## Key Insights for Presentation

For the presentation, I focus on the influence of distance, member age, 
start day of the week, start hour, type of user, and gender over the trip duration. 
I start by introducing the duration variable, followed by the pattern in distance 
distribution, and the pattern in member age distribution. Then show the proportions
depending user type and gender. then plot the relationship between trip duration and
distance using a scatterplot.

Afterwards, I introduce each of the categorical variables one by one. To start,
I use the violin plots of trip duration and distance across user type. I'm only 
looking at the user type plot here since it's the clearest example of how the
categorical user type affect trip duration. The other two categorical variables, 
start day of week and start hour, are covered afterwards, using point plots. Lastly,
I plot heatmaps for showing the hourly usage during the weekdays for subscribers
and customers.
