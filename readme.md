# INTRODUCTION

This is the fifth project of the Data Analyst NanoDegree Program. The aim of this project is to perform an appropriate exploratory data visualization and a comprehensive explanatory data visualization presentation using the appropriate techniques in order to communicate our findings.

# SELECTED DATASET

I choose the Ford GoBike for this project.

Ford GoBike is a Bay Area Bike Share system which share bicycle in California's San Francisco Bay Area. Ford GoBike was re-launched officially in June 2017 as a partnership woth Ford Motor Company. Renting Bikes is a fun and affordable way to get around town easily. 
As of January 2018, the Bay Wheels system had about 10,000 annual subscribers, over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose.

The [Ford GoBike System Data](https://video.udacity-data.com/topher/2021/May/6090815e_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv) includes information about individual rides made in a bike-sharing system. Many features are included in the dataset: Trip Duration (seconds), Start Time and Date, End Time and Date, Start Station ID, Start Station Name, Start Station Lattitude, Start Station Longitude....Member Year of Birth, Member Gender.

## Questions
1. How long does the average trip take? 
2. When are most trips taken in terms of time of day, day of the week, or day of the month of february? 
3. Does the above depend on if a user is a subscriber or customer?
4. What is the average age of bike users?
5. Are female users'trip average time more than males'trip average time? 
6. Which are the most 10 stations with the higher number of starting trip?

## Main findings from Exploratory Data Analysis, and how I organize them in Explanatory Data Analysis

1. Most studied population aged between 25 and 40 years old.
2. The number of trips increases twice a day at the morning between 8am and 10am and at the evening between 5pm and 8 pm.
3. Number of trips is approximately twice more frequent during the weekdays comparing to the weekends.
4. Number of trips fluctuates during February. It looks that this number increases during the first and the third week of February 2019.
5. Most trips'duration range between 2 to 25 minutes with highest occurance at 10 minutes (average of 10.3 minutes).
6. Regarding to gender, females are more likely to spend long time during the bike trip than males.
7. The duration of trips in the weekdays is shorter than weekends. Maybe because users at the weekends have more free time than during weekdays.
8. The 'Market St at 10th St' is the most crowded station where users start their trips  from followed by San Francisco Caltrain Station2.
9. Customers often use the service during Thursday and Friday comparing to Subscribers where the usage of service seems to be similar during the regular weekdays with higher pick on Thursday and Tuesday. Furthermore, the number of use of Bikes is much more higher in subscribers comparing to customers which mean that these users may use the service for daily work and not only for recreational activities.
10. There are subscribers (male and female) more than customers users, and the most subscribers and customers are male which means that males are more likely to practice cycling than females.
11. Subscribers of all ages use the service during the weekdays from Monday to Friday with higher frequency on Thursday. Furthermore, subscribers of all age groups take ride bikes morning between 07:00 to 09:00 am. But evening subscribers of group age 40 to 60 and 60 to 80 use the service between 03:00pm to 06:00pm with an interval narrower than the first age group (20 to 40 years) who took the service starting 04:00pm to 10:00pm. On the other hand, customers show high use of the service morning at 08:00 am and evening at 05:00pm. Customers of both 20 to 40 years group and 40 to 60 years group are more likely to use bikes during the weekend (Saturday and Sunday). Users aged 60 years and above tend to be subscribers more than customers.

Used references:
https://github.com/saiogirala/Ford_Bike_Communicating_Findings/blob/master/Exploratory_Data_Analysis.ipynb

```python

```
