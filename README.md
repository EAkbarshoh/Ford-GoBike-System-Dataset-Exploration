# Ford GoBike System Dataset Exploration
## by (Akbarshox)


## Dataset

> This Dataset contains details of individuals borrowed bikes from a bike-sharing system (called Ford GoBike System) covering the greater San Francisco Bay area.This data set consists of 15 columns and over 183000 observation they are:
 - duration_sec -Duration of rides,in seconds             
 - start_time - Start time            
 - end_time - End time             
 - start_station_id  - Starting  stations' ID      
 - start_station_name - Starting  stations' name     
 - start_station_latitude  - Starting  stations' geographic location
 - start_station_longitude - Starting  stations' geographic location
 - end_station_id          
 - end_station_name        
 - end_station_latitude - Ending  stations' geographic location   
 - end_station_longitude  - Ending  stations' geographic location 
 - bike_id - Bikes' id              
 - user_type - type of user ,whether customer or subscriber           
 - member_birth_year - birth year off customer     
 - member_gender - gender of customer
 - bike_share_for_all_trip - whether enrolled in a program(Only for subscribers)


## Summary of Findings

> - Mean of distribution of duration is 500, which means that most members take bikes for 500 seconds As for age of member common age is about 32,but there is also people aged 80.The most common gender is Males (about 74 %) and then Females(about 24 %).But there are also type of member whose gender is marked as "other"(2 %).Despite fact that men being most frequent members,They don't take long trips(Avg. 680 seconds),this feature can be seen in females (Avg. 790 seconds).When it comes to days of the week,Saturday are least frequent,but most long trips happens in these days Duration,weekdays and user type:the highest overall avegrage is in other and second place for women and last one is men.They all have the same pattern between Monday an Saturday,but in sunday both other and female rise when men fall.Highest points differ,for women it is on Sunday (about 1000 seconds),for men it is on saturday (about 810 seconds).Duration,weekdays and user type:In overall highest durations are in not subscribed customers(all over 1000 seconds) and subscribers are less than 800 seconds in each week.We can see flactution in customers graph.High points are in Saturday and sunday,Sunday being the highest.But in subscribers, highest point is Saturday


## Key Insights for Presentation

> For presentation I am goint to use only findings related to duration and frequency of trips in days of week,by gender,distribution of age also proportion of memerber's genders.Firs I will show visualization of distribution of age and gender, then I use several bivariate visuals of "gender vs duration","Day of week vs avg.duration', and last one will be "Day of week vs gender vs avg. duration"