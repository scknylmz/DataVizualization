# Ford GoBike System Data Exploration
## by Seckin Yilmaz


## Dataset

>  This report explores data from the Ford GoBike System dataset. The data was provided by Udacity via this [link](https://video.udacity-data.com/topher/2023/July/64ac0039_fordgobike-tripdata/fordgobike-tripdata.csv) and was used for this project. The dataset originates from the greater San Francisco Bay area and contains information about individual rides in a bike-sharing system. It includes data on trip duration, participants' birth year, trip start and end times, participant genders, user types, start and end station names, and other variables. Before delving into the data, preliminary data cleaning was performed. This involved removing rows with missing values, replacing outliers, and deriving some variables. These derived variables included the age of participants, start and end days, start hour, month, and age clusters. The initial data assessment showed that the Ford GoBike dataset included 183,412 participants and 16 features with no duplicates. After data cleaning, the exploration dataset consisted of 173,051 observations and 27 features. To analyze the data, I used three types of visualizations: univariate, bivariate, and multivariate. Univariate visualization focuses on individual variables to understand their distribution. Bivariate visualization explores the relationship between two variables. I also extended bivariate visualization to multivariate, examining relationships among three or more variables for a comprehensive understanding."

## Summary of Findings

> In the exploration, I found a weak positive relationship between age and duration in seconds. But when I cluster the ages as age < 35 (Younger) | 35 < age < 50 (Midlifer)| age> 50 (Elder) it observed that elders have long duration than others. In simpler terms, when people get older, they usually spend more time finishing their journey, perhaps because their energy decreases with age. The results also indicated that people who subscribed required less time to finish the journey compared to customers. Men seemed to finish the trip faster than women based on their gender. The results also showed that there was no age difference between people who subscribed and those who were customers. 

> When I looked at how long trips took and which days they started on, I discovered that trips were quicker on weekdays compared to weekends (Saturday and Sunday).This implies that people are enjoying their rides at holidays. When I looked at how many trip performed by hours, I discovered that the most popular hours are between 10:00-17:00 at weekends. Also, the most popular hours are between 07:00-10:00 and 16:00-19:00 at weekdays because of work hours. 

> When I look at how many times stations are used as starting points by day, On weekends, the two most well-liked stations are 58 and 3. Even though 67 isn't favored on weekends, it's the top station on weekdays. Station 58 enjoys popularity both on weekends and weekdays. When I look at the station numbers where people start and finish their rides, I notice that the top 7 stations are the same for both starting and ending, even though the order might be different. Additionally, Station 67 is the most popular choice for ending a ride (over 4500 times), but it's not as commonly used as a starting point (around 3400 times). This suggests that when people arrive at Station 67 using Ford GoBike, they don't often choose to return from there.

> I discovered that no matter the kind of user, men finished the journey more quickly than women.

> In addition to the primary factor of concern, I examined the correlation between the duration of a journey and whether a participant shared a bicycle for the entire journey. The findings indicated that individuals who shared a bicycle for the entire journey completed their trips more quickly than those who did not share a bicycle for the entire journey.

## Key Insights for Presentation

> At the presentation, I mainly concentrated on examining how the day of the week and hours of the day affect the number and duration of trips. I chose these variables for the presentation because they displayed a distinct relationship without any uncertainty. To begin, I will display the count of trip data after it has been cleaned. After that, I will gradually introduce the categorical variables to gain a better understanding of the connection between each categorical variable and the trip count. This relationship will be further illustrated using box-plot, bar charts and scatter plots.
