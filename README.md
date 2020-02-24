# World_Weather_Analysis

## Challenge

**Resources:**  
+ Jupyter-Notebook version 6.0.3
+ Python version 3.7.6


**File Descriptions:**
+ Weather_Database.ipynb creates a random list of 500+ cities, and retrieves current weather conditions from openweathermap.org.  A dataframe of relevant data is produced and exported to the data folder (data/WeatherPy_challenge.csv).  The following fields are included:
  + City
  + Country
  + Date
  + Latitude
  + Longitude
  + Weather (short description)
  + Current Weather Description
  + Max Temperature (Fahrenheit)
  + Percent Humidity
  + Percent Cloudiness
  + Wind Speed
  + Rain (inches reported in last 3 hours)
  + Snow (inches reported in last 3 hours)


+ Vacation_Search.ipynb uses the WeatherPy_challenge.csv file and asks the users to narrow the list of cities by a minimum and maximum temperature range, and whether or not they would like it to be raining or snowing.  Using gmaps, a nearby hotel is added to the filtered list of cities and a file is exported to the data folder (data/WeatherPy_vacation.csv).  The fields included in the file are:
  + City
  + Country
  + Max Temperature (Fahrenheit)
  + Current Weather Description
  + Latitude
  + Longitude
  + Hotel Name
+ In Vacation_Search.ipynb a marker layer map is created for the vacation spots with a pop-up marker for each city.  The pop-up marker includes:
  + Hotel Name
  + City
  + Country
  + Current weather description and max temperature
+ Examples of the maps from Vacation_Search.ipynb are included in the image folder
  + WeatherPy_vacation_map.png shows the full marker layer map
  + WeatherPy_vacation_map_markers.png shows a zoomed in view with a few pop-up markers open
#### WeatherPy_vacation_map.png
![](https://github.com/kenwelsh/World_Weather_Analysis/blob/master/image/WeatherPy_vacation_map.png "Vacation Map")
#### WeatherPy_vacation_map_markers.png
![](https://github.com/kenwelsh/World_Weather_Analysis/blob/master/image/WeatherPY_vacation_map_markers.png "Vacation Map With Pop-Up Markers Open")
+ Vacation_Itinerary.ipynb uses the WeatherPy_vacation.csv file.  Four cities are selected for the itinerary.  Using gmaps, a direction layer map is generated to show the driving route between the four cities. In addition, a marker layer map for the four cities is created with a pop-up showing:
  + Hotel Name
  + City
  + Country
  + Current weather description and max temperature
+ Examples of the maps generated in Vacation_Itinerary.ipynb can be found in the image folder
  + WeatherPy_travel_map.png shows the driving route between the four cities
  + WeatherPy_travel_map_markers.png shows the four cities with the pop-up marker containing hotel and other information open
#### WeatherPy_travel_map.png
![](https://github.com/kenwelsh/World_Weather_Analysis/blob/master/image/WeatherPy_travel_map.png "Itinerary Route Map")
#### WeatherPy_travel_map_markers.png
![](https://github.com/kenwelsh/World_Weather_Analysis/blob/master/image/WeatherPy_travel_map_markers.png "Itinerary Cities With Pop-Up Markers Open")
  
