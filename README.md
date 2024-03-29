# Uber-Lyft-Price-Prediction
Analyzing the factors affecting or driving the demand of Uber vs Lyft. We are also planning to analyze the pattern of prize surge due to extreme weather conditions in Uber Vs Lyft. Source of the data: https://www.kaggle.com/uber-lyft-cab-prices

# Problem Statement
* What factors are driving the demand of Uber and Lyft?
* How these weather and time factors affecting the surge in price of these cabs?

# Dataset Information
We are using two datasets:
* cab_rides.csv (693k records with 10 attributes)
* weather.csv (6276 records with 8 attributes)

# Attribute Information

## CAB_RIDES.CSV DATA

Name | Description
-----|-------------
distance|Distance between source and destination
cab_type|Uber or Lyft
time_stamp|epoch time when data was queried Travel
destination|destination of the ride 
source|the starting point of the ride
price|price estimate for the ride in USD
surge_multiplier|the multiplier by which price was increased, default
id|unique identifier
product_id|Uber/lyft identifier for cab-type
name|Visible type of the cab eg: Uber Pool, UberX

## WEATHER.CSV DATA

Name | Description
-----|-------------
temp|Temperature in F
clouds|Clouds
pressure|pressure in mb 
rain|rain in inches for the last hr
time_stamp|epoch time when row data was collected
humidity|humidity in %
wind|wind speed in mph
