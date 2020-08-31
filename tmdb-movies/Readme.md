# TMDB-movies
## by Eunice Oduwole

## Dataset

This document examines 192082 dataset containing information about individual  rides made in a bike-sharing system covering the greater San Francisco Bay area. The attribute included four feature, with other attribute such as bike_share_for_all_trip, start_station_name, start station id. Two more features were added such that we have entries for time in term of day and time (extracted from the start time column).  Dataset can be found [here](https://www.lyft.com/bikes/bay-wheels/system-data)

## Wrangle Process
I added two more features were added such that we have entries for time in term of day and time (extracted from the start time column). And changed the days of the week column into a ordinal categorical datatype,  user type and bike share for all was changed into a nominal categorical data, startime and endtime was also chnage to datetime and bike id was changed into strings. 



## Summary of Findings
I looked at the characteristics of bike hiring that could be used to predict trip duration. The main focus was on the day of the week, user type (subscriber or customer i.e casual user) and hours of the day. 
I found the distribution of the hour of day is roughly bimodal, with the first peak roughly between 8 and 10, and the second peak between 16 and 20. There appears to be a steep jump right before 16. It was observed that most trips are taken between Monday to Friday. While Thursday seems to have a higher frequency than other days. Location had no impact on the trip duration. It is surprsing to see that more customer has a higer trip duration in contrast to the subscriber. Thus, been a subscriber or customer doesn't have a limit how long an individual can ride. I expected subcriber to have the benefit of riding a longer distance, but appears that it doesn't matter if the individual is subscriber or casual users (customer). It was also interesting to discover that at 3:00 in the morining there is a higer trip duration, this I guess could be as a result of few avilablle transportation options at that time if the day. The longer trips are taken during the weekends (Sunday and Saturday), this could be because its a free time of everbody. Starting from 8:00 in the morning, the trip duration is about 520 seconds on average.






## Key Insights for Presentation
For the presentation I focused more on the impact of day of the week, hour of the day and user type on trip duration. 

I started by showing the distribtions of all variables of interest. Then I showed the plot of intercation user type versus trip duration, trip duration versus day of the week. I also introduced a plot for Trip duration and hour by days of the week, and Trip duration and hours of the day by users. The last two graph were added to further emphasis on the finding. 
