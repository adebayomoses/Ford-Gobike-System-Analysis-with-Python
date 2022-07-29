# (Dataset Exploration Title)
## by (Adebayo  Moses)


## Dataset

> Provide basic information about your dataset in this section. If you selected your own dataset, make sure you note the source of your data and summarize any data wrangling steps that you performed before you started your exploration.

The data consists of information regarding over 184,000 samples, There are 183,412 rides in the dataset with 16 features (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender and bike_share_for_all_trip). 

The dataset can be found in the Udacity classroom library (https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).



## Summary of Findings

> From the analysis, we found that there is a negative non linear strong relationship between time duration and longitude length and positive non linear strong relationship between time duration and latitude length , which is highly concentrated between -0.1 and 0.1.
The Customer riders primarily utilize Cyclistic bikes on the weekends especially on friday and saturday and less frequently during the weekdays, compared to the Subscribers.
This analysis found that there is no specific relationship bewteen time duration and riders age,also, their is no strong relationship between age,latitude length and longitude length.
More riders are Subscribers of Ford GoBike System than are Customers.
The graph above indicates that the first 20 stations in the graph above contains the majority of the cyclists' start and end station names. The most commonly used stations are Embarcadero station, San francisco and Powell Brat station, while 16th St Depot station have only been used twice, by two customer riders.
Additionally, we discovered that Subcribers and customers riders rode their bikes more frequently on the weekends (mostly Saturday and friday) than on other days of the week.


## Key Insights for Presentation

> For the presentation, I focus on just the main factor affecting the riders gotten from the dataset
and leave out most of the scatter plot relationship. I start by introducing the
price variable, followed by the limitation of the study, then obseravtion with the plot.

Afterwards, I introduce each of the categorical variables one by one. To start,
I use the bar plots of rider weekday, follow by the histogram plot of age distribution. The other two categorical variables, user type and member gender, are covered afterwards, using barplot and facetgrid. I've made sure to use different color palettes for each quality variable to make sure it is clear that they're different between plots.
