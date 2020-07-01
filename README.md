# Analysis with Ford GoBike System Data
by Pankaj 

Jun,2020

## Dataset

The dataset consists of information about 500,000 bike hiring.The dataset can be found out on https://s3.amazonaws.com/fordgobike-data/index.html. I have used the 2017 GoBike System Dataset.
Here are the fields provided to us within the primary source dataset . 

- Duration in sec
- start_time
- end_time                 
- start_station_id         
- start_station_name       
- start_station_latitude   
- start_station_longitude  
- end_station_id           
- end_station_name         
- end_station_latitude    
- end_station_longitude    
- bike_id
- user_type

## Files 



## Summary of the findings
The people are using bikes for short duration on weekdays and for longer duration on weekdays and the count of hiring bikes are much larger on weekdays than on weekends. One more finding which i got is that the people who has subscribed are using hiring bikes even for smaller work than people who have not subscribed and as the weather is changing the people are choosing bikes for nearby places which is kind of expected.

## Key Insights for Presentation

- The distribution of biking durations is right skewed. 
- The count of bike hire on weekends are much lower than that at weekdays.
- The Subscriber hire count is way much higher than that of Customer.
- The person on average hire bikes for larger duration on weekends than that on weekdays.
- Most of the bike are hired around 8-9am and 5-6pm on weekdays.

## Software Used
These are the following packages I used throughout this project.

- pandas 
- matplotlib.pyplot 
- seaborn 
- numpy
- warnings


