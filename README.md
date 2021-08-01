# World_Weather_Analysis

Module 6: WeatherPy with Python API

Completed by Angela Kumar

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

<img width="584" alt="Heat Map of Temperatures" src="https://user-images.githubusercontent.com/85860367/127759631-6b930c35-08ee-4af9-acdc-2aee4a4ad5f6.PNG">

Percent humidity

<img width="584" alt="Heat Map of Humidity" src="https://user-images.githubusercontent.com/85860367/127759639-44a40b20-f521-4999-a7aa-54d435a106b0.PNG">

Percent cloudiness

<img width="584" alt="Heat Map of Cloudiness" src="https://user-images.githubusercontent.com/85860367/127759648-2b8cb02a-581b-41d2-a0d6-b26754efa412.PNG">

Wind speed

<img width="668" alt="Heat Map of Wind" src="https://user-images.githubusercontent.com/85860367/127759653-c7481854-7f11-4170-9521-528ac115a5ce.PNG">

Weather description (for example, clouds, fog, light rain, clear sky)

Add the weather data to a new DataFrame 

<img width="584" alt="DataFrame with Weather Description 2" src="https://user-images.githubusercontent.com/85860367/127759540-355e55a5-91dc-4657-a58c-3dbcf560a309.PNG">

<img width="670" alt="Heat Map of Preferred Cities" src="https://user-images.githubusercontent.com/85860367/127759606-9d25bcd4-2cec-447d-9cd9-7b2267a73090.PNG">

<img width="676" alt="Preferred Cities with Markers" src="https://user-images.githubusercontent.com/85860367/127759585-3be82a81-c6e6-4872-a497-8ba756c934ac.PNG">

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
<img width="430" alt="Deliverable 2 DataFrame with Hotel" src="https://user-images.githubusercontent.com/85860367/127759439-60c84cc0-71dc-44ff-9707-e3b7a58440c0.PNG">

<img width="669" alt="Hotel DataFrame" src="https://user-images.githubusercontent.com/85860367/127759456-d9ec4a76-e7bf-4dd5-bbdc-f5b530d3e6b5.PNG">

<img width="679" alt="Deliverable 2 Vacation Map" src="https://user-images.githubusercontent.com/85860367/127759488-d396b09a-c412-4a3f-9dc9-f8ae8b64b900.PNG">


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

<img width="672" alt="Del 3 Headers of vacation itinerary" src="https://user-images.githubusercontent.com/85860367/127759253-255bbc4a-2187-4fac-9c48-f678630107aa.PNG">

<img width="682" alt="Del 3 WeatherPy_Travel Map" src="https://user-images.githubusercontent.com/85860367/127759262-f4d6bb1c-9c1b-4c87-8b98-238615ecb082.PNG">

<img width="681" alt="Del 3 WeatherPy_Travel Map with Markers" src="https://user-images.githubusercontent.com/85860367/127759272-2077dcb9-3901-43b8-b0ba-b519d88a1740.PNG">


Be sure to have the following in the Vacation_Itinerary folder:

The Vacation_Itinerary.ipynb file

The WeatherPy_travel_map.png image

The WeatherPy_travel_map_markers.png image

**Summary**
This was a way to utilize the minimum and maximum temperatures to plan a vacation.  The choices or possibilities were boundless around the world. The criteria was to select 4.  I started out in the tropics, went into the woods, and then ultimately selected California and Baja California as it had the best weather, great hotels, and things to see or do.  The one thing that I was unable to do, was prevent the markers from overlapping, so I selected the beginning and ending markers on my itinerary. Overall this was a fun project to learn and experience.

