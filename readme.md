# Ford GoBike System Data Analysis
## by Abdallah Badran


## Dataset

> The dataset consists of 183412 members of Ford GoBike system with 19 fetaures after perfoming some feature engineering and data wrangling. An 'age' column is extracted from the given 'member_birth_year' column and missing values are filled with average age. Also, 'start day' and 'start hour' columns extracted from 'start time' column. The time columns as 'start_time' and 'end_time' are converted from string to datetime data typ.


## Summary of Findings

> Most trips are on weekends on Thursdays and the least trips are on the start of the week on Saturdays and Sundays. 
> Most of trips starts between 7 am and 9 pm with one peak at 8 am and the other peak is at 5 pm. 
> Taking into consideration that we have substituted missing values with the mean, most of the members' ages are between 24 and 40 with peaks between 25 and 26, 30 and 31 and the greatest peak is between 34 and 35 which means that most of members are in their mid thirties. Also there exist some outliers like the one of age 141.
> 160 k of users are subscribers while only 20 k of users are customers.
> The trip durations are of normal distribution with a peak between 600 and 700 seconds which is 10 minutes and 11.67 minutes with frequency of 10k. 
> Only 20k members which is about 11% of all members are enrolled in the 'Bike Share for All' program. 
> Taking into consideration missing values, more than 120k of members are males while 40k are females and less than 2500 others
> Customers have larger trip durations than subscribers in average, customers have about 1400 seconds (23 minutes) while subscribers have about 600 seconds (10 minutes) in average. 
> There is no significant difference in trip duration whether a member is in the 'bike share for all' program or not. 
> Members that starts their trips at 2 am or 3 am have the longest trip duartions on average. 
> Members who are not males nor females have the longest trip duration in average. 
> It is interesting to know that members ate their mid fourties in average starts their trips early at 4 am, and there is a slight decrease in ages as we go towards the mid and end of day. 
> Start and end stations are distributed among four main clusters, the largest cluster cnetred at -122.25 longitude and 37.85 latitude, then a smaller cluster at -122.4 longitude and 37.78 latitude, then smaller one at -121.95 longitude and 37.4 latitude then the smallest on at -121.85 longitude and 37.35 latitude
> Members rather than males or females always start their trips from the clusetr of stations that is centered at -122.25 longitude and 37.85 latitude. Also the cluster at -121.85 longitude and 37.35 latitude almost occupies males rather than any other gender
> Most of members who are in the 'bike share for all' start their trip from the cluster of stations that is centered at -122.25 longitude and 37.85 latitude

## Key Insights for Presentation

> For the presentation I focus on the distribution of the trip durations and the hours at which the durations are the longest and the effect of user type on the trip duartion 