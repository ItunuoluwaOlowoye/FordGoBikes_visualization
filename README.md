# Ford GoBikes Data Exploration
## by Itunuoluwa Olowoye

## Dataset

## Introduction
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay, United states. The dataset can be downloaded [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).
This project is aimed at exploring this dataset, understanding the trends of users of the bike sharing company and giving high-level markeing advice.


## Summary of Findings

**Market St at 10th St** starts the most trips and **San Francisco Caltrain Station 2 (Townsend St at 4th St)** ends the most trips. Subscribers account for about 90% of the customer base. This customer base are more than 70% male, and most are between 20 to 40 years old.

Generally, trip duration is heavily skewed to the right with a log-normal distribution.

Although subscribers make up the bulk of the customer base, they spend less time on trips than customers. They are however very active because they start and end the most number of trips.

Gender and the decision to share bikes throughout the trip does not significantly affect trip duration. There are more male customers than other genders, and more male subscribers too.

Some long trip durations (>40,00 seconds) seem to have happened before dawn on certain days like the 9th and 28th of February. This may need further investigation to ascertain the accuracy of the entries.

While trip duration and age of users, at first glance, may not seem to be relatable, the heat map correlation showed that most adults (20 to 40 years old) spend roughly 300 to 1000 seconds on trips, meanwhile trips could last as long as 80,000 seconds.

The relationship between user type, trip duration and gender/age was strengthened. Earlier, we observed that customers took the longest trips. Now we know that female customers took the longest trips.

The average age of all user types regardless of gender is above 30 years old.

## Key Insights for Presentation

For the presentation, I focus on the highest start and destination bike stations. This will guide logistics planning for the bike sharing company - they know which bike stations will need more bikes due to the high demand.

I also focus on the gender distribution to help the company understand the importance of diversity, equity and inclusion.

Finally, I focus on the relationship between trip duration, usertype and age. Marketing strategy can be tailored towards getting more people to take longer rides and advertise its safety since older people are using it too.
