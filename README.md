This project pulls real time wave forecast data from some of my favorite surf spots from the Surfline API.
# Tools Used
Used python, requests to pull the data from the Surfline API, Pandas for cleaning and tranforming the JSON data, Matplotlib and seaborn for visualization
# What was Done
Connected to the surfline API and pulled 5 days of hourly forecasts data for some of my favorite surf spots
Parsed the JSON repsonse into a Pandas Dataframe
Cleaned the data set and analyzed patterns in wave height overtime
# Problem
Data was originally a dot/line plot which didn't make too much sense and didn't look visually appealing so converted it into a Histogram
Surfline also only allows you pull 5 days of data which is what led me into doing the NOAA project to get me more accurate forecasting
# Plot 
![Wave Height Histogram](wave_histogram.png)
