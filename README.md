# World_Weather_Analysis

Module 6: WeatherPy with Python API

**Overview**

Practice analysis, visualization, and statistical skills by retrieving and analyzing weather data for a hypothetical travel company, PlanMyTrip. Successfully completing the tasks will draw on knowledge of Python, decision and repetition statements, data structures, Pandas, Matplotlib, and SciPy statistics.
Plot the relationship between latitude and weather for cities around the world using Python, Pandas, and APIs.

**Background**

Jack loves the PlanMyTrip app and the Beta testers love it too. As with any new product, recommendations have been given to take the app to the next level. One recommendation is adding the weather description to the weather data already retrieved in this module. Second, The beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From that list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, a travel route between the four cities and a marker layer map.

**Resources**

•	Data Source: Weather_Database.ipynb; The Vacation_Search_starter_code; The Vacation_Itinerary_starter_code 

•	Data File: file.csv

•	Software: Matplotlip 3.2.2, Python 3.10, Visual Studio Code 1.50.0, Anaconda 4.8.5, Jupyter Notebook 6.3.0, Pandas, Google API, 
  Websites: Google Maps, OpenWeatherMap

**Deliverables**

**Deliverable 1:** Retrieve Weather Data

Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data you gathered in this module, use your API skills to retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data.

Retrieve all of the following information from the API call: 

Latitude and longitude
Maximum temperature
Percent humidity
Percent cloudiness
Wind speed
Weather description (for example, clouds, fog, light rain, clear sky)
Add the weather data to a new DataFrame 

Export the DataFrame as WeatherPy_Database.csv into the Weather_Database folder 

Be sure to have the following in the Weather_Database folder:

The Weather_Database.ipynb file

The WeatherPy_Database.csv file

**Deliverable 2:** Create a Customer Travel Destinations Map

Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

Input statements are written to prompt the customer for their minimum and maximum temperature preferences. 
A new DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped. 
The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped. 
The DataFrame is exported as a CSV file into the Vacation_Search folder and is saved as WeatherPy_vacation.csv. 
A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information: 

Hotel name
City
Country
Current weather description with the maximum temperature
The marker layer map is saved and uploaded to the Vacation_Search folder as WeatherPy_vacation_map.png. 

Be sure to have the following in the Vacation_Search folder:

The Vacation_Search.ipynb file

The WeatherPy_vacation.csv file

The WeatherPy_vacation_map.png image

**Deliverable 3:** Create a Travel Itinerary Map

Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

You will earn a perfect score for Deliverable 3 by completing all requirements below:

Four DataFrames are created, one for each city on the itinerary. 
The latitude and longitude pairs for each of the four cities are retrieved. 
A directions layer map between the cities and the travel map is created and uploaded as WeatherPy_travel_map.png. 
A DataFrame that contains the four cities on the itinerary is created.
A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as WeatherPy_travel_map_markers.png. Each marker has the following information:

Hotel name
City
Country
Current weather description with the maximum temperature

Be sure to have the following in the Vacation_Itinerary folder:

The Vacation_Itinerary.ipynb file
The WeatherPy_travel_map.png image
The WeatherPy_travel_map_markers.png image

