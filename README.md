# CO2-levels-and-Global-Temperatures
This project is coded in Python and uses two datasets from Kaggle.com: co2.csv and GlobalTemperatures.csv. 

# Objective
The objective of the project is to show a correlation between global Carbon Dioxide (CO2) levels in parts per million (ppm) and Global Temperatures in Celsius. The range for the years that I've decided to use is 1970-2015.

# Method
I elected to create two dataframes from the two seperate files that pull the years and the correlating numbers (co2 ppm and temperature (C)) from the data provided.
I created a line graph for the CO2 data to display the noticeably consistent increase in CO2 levels over time. Then I created a bar graph of the Global Temperatures data during the same time frame to show the temperature variability through time with an overall noticeable trend with the eye test that revealed low and high temperatures were steadily increasing. Following graphing, I calculated the correlation coefficient and p-value between the two limited data sets to determine what the numbers revealed about the relationship between the two. 


# Result
The graphs reveal climbing CO2 levels through time, as well as an overall trend of increasing global temperatures. At face-value, they appear to be related (it should be noted that many climatologists are in agreement with this theory). The correlation coefficient and p-value calculated from the data I used, .045 and .8 respectively, indicate a minimally positive to no correlation found. Further tests with a wider data range and more specific temperatures (such as sea temperature vs land temperature) could result in a more positive correlation discovered.


