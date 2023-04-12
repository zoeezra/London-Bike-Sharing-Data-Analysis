# London-Bike-Sharing-Data-Analysis
Understanding the hourly bike demands of the London Bike Sharing System using a supervised machine learning model

## The Data
The data for this project was taken from [Kaggle](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset). It originally had one column for the timestamp,
which included the date and time. I separated the timestamp into the date, month, day, year, and hourly time so that I could easily work with the data. 
Additionally, I created another column that indicated which day of the week that date was. 

Here is a guide to the different variables in the updated dataset:
1. `timestamp` - contains both time and date that corresponds to the number of bike trips 
2. `day_of_week` - day of the week
3. `date` - date in timestamp
4. `month` - month in timestamp
5. `day` - day in timestamp
6. `year` - year in timestamp
7. `time` - hourly time in 24H format
8. `category` - hourly time in numerical format
9. `cnt` - the number of bike trips/users within that timeframe
10. `t1` - the real temperature in C
11. `t2` - the temperature in Celcius "feels like"
12. `hum` - the humidity in percentage
13. `wind_speed` - wind speed in km/h
14. `weather_code` - category of the weather (1 - Clear Skies, 2 - Scattered Clouds, 3 - Broken Clouds, 4 - Cloudy, 7 - Light Rain/Rain, 10 - Rain with Thunderstorm,
26 - Snowfall, 94 - Freezing Fog)
15. `is_holiday` - a boolean field where 1 holiday / 0 non holiday
16. `is_weekend` - a boolean field where 1 if the day is weekend
17. `season` - a category field of the meteorological seasons (0 - Spring, 1 - Summer, 2 - Fall, 3 - Winter)
