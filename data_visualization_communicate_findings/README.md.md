# Ford GoBike System Data Visualization and Analysis

## Dataset

The data consists of information regarding 210,563 Bay Wheels's trip data captured during Aug 2019. Dataset includes
- Trip Duration (seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID 
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
- Member Year of Birth
- Member Gender

The dataset can be downloaded from lfty.com official website [here](https://s3.amazonaws.com/baywheels-data/201908-baywheels-tripdata.csv.zip), with feature documentation available [here](https://www.lyft.com/bikes/bay-wheels/system-data).


## Summary of Findings

In the exploration, I found following：

In terms of user profiling
- Majority users are from 20-40 age group. 
- Rides made by male users are more than triple that of female users
- Rides made by subscribers are more than double that of customers

In terms of ride statistics
- There is a clear trend that rides made on weekdays almost double that of weekends
- During weekdays, morning peak hours start from 7am to 9am, afternoon peak hours start from 5pm to 6pm.
- During weekends, there is no obvious peak hours, users ride primarily from 9am to 8pm.

By comparing behavior between Customer group and Subscriber group. I noticed following:
- Users from Customer group generaly ride longer duration than Subscriber group, irrespective of gender.
- In terms of trip distance, Customer group ride longer distance than Subscriber group.
- In terms of trip peak hours, there is no difference between Customer group and Subscriber Group.

When I compared ride start hours and weekdays between Customer group and Subscriber Group. Each group exhibits different ride patterns. 
- Customer group ride on weekdays as frequently as on weekends, while Subscriber group primarly ride on weekdays.
- On weekdays, both Customer group and Subscriber group ride more in peak hours.

## Key Insights for Presentation

My presentation is focus on different travelling patterns bewteen 

**Customers use the bike sharing system more often on weekends:**
- weekdays: most bike rides hapen around 8-9am and 5-6pm with the peak on Fridays around 5pm
- weekends: most bike rides happen between 10am - 8pm with the peak on Saturdays around 2pm
**Subscribers use the bike sharing system mainly on weekdays:**
- weekdays: most bike rides hapen around 8-9am and 5-6pm with the peak on Tuesdays around 8am
- weekends: bikes are still rented but there is a significant drop in numbers of rented bikes throughout the entire weekends
