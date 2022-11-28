# Soeul-Bike-Sharing-Demand-Prediction
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the Seoul based on some factors.

**#Data Summary:**

The dataset contains weather information (Temperature, Humidity, 
Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), 
the number of bikes rented per hour, and date information.

1.Date: year-month-day
 2.Rented Bike count -Count of bikes rented at each hour 
 3.Hour -Hour of the day
 4.Temperature-Temperature in Celsius 
 5.Humidity -% 
 6.Windspeed -m/s 
 7.Visibility -10m
 8.Dew point temperature –Celsius
9.Solar radiation -MJ/m2 
10. Rainfall -m
11.Snowfall -cm 
12.Seasons -Winter, Spring, Summer, Autumn 
13.Holiday -Holiday/No holiday 
14.Functional Day -NoFunc(Non-Functional Hours), Fun(Functional hours)
*This Dataset contains 8760 lines and 14 columns. 
* Three categorical features ‘Seasons’, ‘Holiday’, & ‘FunctioningDay’. 
* One Datetime features a ‘Date’. 
* We have some numerical type variables such as temperature, humidity, wind, 
visibility, dew point temp, solar radiation, rainfall, and snowfall which tell the 
environmental conditions at that particular hour of the day.

**#conclusion:**
1. ‘Hour’ of the day holds the most important feature.
2. Bike rental count is mostly correlated with the time of the day as speak at 10 
am morning and 8 pm evening.
3. We observed that the bike rental count is high during working days than on 
nonworking days.
4. We see that people generally prefer to bike at moderate to high temperatures, 
and when a little windy
5. It is observed that the highest number of bike rentals counts in the Autumn & 
Summer seasons & the lowest in the winter season. We observed the highest 
number of bike rentals on a clear day and the lowest on a snowy or rainy day. 
We observed that with increasing humidity, the number of bike rental counts 
decreases
