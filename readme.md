# FordGoBike Trip Data
## by Abdulrahman Alyahya


## Dataset

The forgobike trip data are 3,254,324 rides that happend in 2017, 2018 and 2019 (until May). The dataset is contain 16 columns before I did cleaning. Some attributes duration_sec, start_time, end_time, start_station_id, start_station_name, and member_age. I downloaded the data set from [HERE](https://www.lyft.com/bikes/bay-wheels/system-data).
<br>
I delete all user more than 60 years old because most users are between 18-58 year old. Also I creared new columns like age_category, duration_min, distance_km, start_time month, monthly, day, and hour. After I cleaned my data and craeted new columns the data became 3,177,270 records and 25 columns.
<br>
![alt text](https://pbs.twimg.com/profile_images/1139290064599412736/oqGCNt4a_400x400.png)
<br>

## Summary of Findings

In the exploration, I found that there are two types of user: 
* Subscriber 
* Customer <br>

I realised the subscriber users have the highset number of trips at 8.AM and 5.PM and that because the work hours (start and end work). Also the rides trips between 12.AM and 5.AM has the lowest number of rides and that it's hours sleep. And on the week day I found the weekday have  more trpis per day than weekend day. Unlike customer users.<br>
The customer users the number of trips are start growing from 7.AM to 5.PM (highset) then it's will be decreased. Also they have the highset trips on weekend.<br>
Also I found most ages are between 31 to 40 years old for subscriber users, and the customer users are between 21 to 30 years old. The number of trips are growing up for 21-30 years old over time, In 2017 and 2018 the ages between 31 to 40 years have the highset trips, but satrt with 2019 I found the ages between 21 to 30 years are the highset.

## Key Insights for Presentation

For the presentation, I focus on just the  user types, gender, and age. I start by showing the percentage of bike rides for all user types subcriber and customer, it's show the subcriber users are 84.2% and that mean the customer users are 15.8%.<br>
Then I plot the number of bike rides (trips) for each day based on gender that mean it's plot the number of trips for evryday to show trips number for each gender on all days.<br>
In the end I show the number of bike rides over time based on age category. I divided members age into 5 categories in cleaning section:
- Age between 11 to 20 
- Age between 21 to 30
- Age between 31 to 40
- Age between 41 to 50
- Age between 51 to 60<br>
