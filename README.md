## Visualization in R

The dataset was taken from Kaggle: https://www.kaggle.com/jsphyg/weather-dataset-rattle-package 


This dataset contains daily weather observations from numerous Australian weather stations. 
Variables:
<br>. <b>Date</b> The date of observation 
<br>. <b>Location</b> The common name of the location of the weather station 
<br>. <b>MinTemp</b> The minimum temperature in degrees celsius 
<br>. <b>MaxTemp</b> The maximum temperature in degrees celsius 
<br>. <b>Rainfall</b> The amount of rainfall recorded for the day in mm 
<br>. <b>Evaporation</b> The so-called Class A pan evaporation (mm) in the 24 hours to 9am 
<br>. <b>Sunshine</b> The number of hours of bright sunshine in the day. 
<br>. <b>WindGustDir</b> The direction of the strongest wind gust in the 24 hours to midnight 
<br>. <b>WindGustSpeed</b> The speed (km/h) of the strongest wind gust in the 24 hours to midnight 
<br>. <b>WindDir9am</b> Direction of the wind at 9am 
<br>. <b>WindDir3pm</b> Direction of the wind at 3pm 
<br>. <b>WindSpeed9am</b> Wind speed (km/hr) averaged over 10 minutes prior to 9am 
<br>. <b>WindSpeed3pm</b> Wind speed (km/hr) averaged over 10 minutes prior to 3pm 
<br>. <b>Humidity9am</b> Humidity (percent) at 9am 
<br>. <b>Humidity3pm</b> Humidity (percent) at 3pm 
<br>. <b>Pressure9am</b> Atmospheric pressure (hpa) reduced to mean sea level at 9am 
<br>. <b>Pressure3pm</b> Atmospheric pressure (hpa) reduced to mean sea level at 3pm 
<br>. <b>Cloud9am</b> Fraction of sky obscured by cloud at 9am. This is measured in “oktas”, which are a unit of eigths. It records how many eigths of the sky are obscured by cloud. A 0 measure indicates completely clear sky whilst an 8 indicates that it is completely overcast.
<br>. <b>Cloud3pm</b> Fraction of sky obscured by cloud (in “oktas”: eighths) at 3pm. See Cload9am for a description of the values 
<br>. <b>Temp9am</b> Temperature (degrees C) at 9am 
<br>. <b>Temp3pm</b> Temperature (degrees C) at 3pm 
<br>. <b>RainToday</b> Boolean: 1 if precipitation (mm) in the 24 hours to 9am exceeds 1mm, otherwise 0 
<br>. <b>RISK_MM</b> The amount of next day rain in mm. Used to create response variable 
<br>. <b>RainTomorrow</b> A kind of measure of the “risk”.

<br>There are 2 versions:
<br>Interactive - to get better insights from dataset by applying filters (by Cities, Year) using Shiny functionality (<b>AdvRdashboard-1.1-interactive.Rmd</b>).

<br>Static (<b>AdvRdashboard-1.1-Report.html</b>).
