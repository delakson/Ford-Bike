# Ford Bike-Sharing Data Exploration

## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.The source data (Ford GoBike System Data) is available at : https://www.fordgobike.com/system-data.
The above mentioned Data Set focuses on information with regard to the individual rides undertaken in a bike-sharing system expanded over the greater San Francisco Bay Area.
   
The Features included in the Data are as follows :

- Member Year of Birth
- Member Gender
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
- Trip Duration(in seconds)
- Bike ID
- Start Time and Date
- End Time and Date
- Start Station ID
- End Station ID
- Start Station Name
- End Station Name
- End Station Latitude
- End Station Longitude
- Start Station Latitude
- Start Station Longitude
- Bike_share_for_all_trip


## Summary of Findings

In the exploration:

- Trip duration has a long-tailed distribution, with a lot of short trip time, and few on the long trip time. 
When plotted on a log-scale, the Trip duration distribution has a bell curve shape, with the peak between 3mins and 30mins.

- The use of bike services is the most during peak hours(0800hrs and 1700hrs) which implies the resumption and closing hours of a weekday.

- Plotting Duration Trip and Gender on a boxplot also trimming duration to max 2500 sec to get clearer picture,shows that higher percentage of female and other rides longer trips then males. Though quantity of male riders are very high then other and female

- Plotting Duration Trip and user_type (customers or subscibers) on a boxplot also trimming duration to max 2500 sec to get clearer picture,shows that higher percentage of customers are taking longer trips then compared to subscribers.

- Subscribers tends to have stable Trip duration usage on a daily basis but abit high trip duration at the early hour of the day as compared to Customers with flexible trip duration customer aslo tend to have high trip duration at the early hour of the day (3AM)


## Key Insights for Presentation

For the presentation, I focus on Trip duration , followed by the pattern in Hours  distribution

Afterwards, I introduce Bivariate and multibariate chart  variables one by one. Ranging from,
the violin plots of Duration and Gender , Boxplot of Gender and Age of User , countplot of Gender and bike share trip,
heat map of Trip start day and Gender.

