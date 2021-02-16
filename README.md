# WeatherPY



## Project Overview

Jack and & I are working on a project for a new app called PlanMyTrip that will be a great influence to our clients' travel goals.  We've already made progress and look forward to beta testers' feedback.  

Upon leaving our meeting with Beta-testers, as with any new project, they've recommended some changes to take the app to the next level.  The app will not only recommend travel destinations and ideal hotels based upon clients' temperature preferences, but it will also provide a weather description! The more information we can provide our clients, the better.  The app will also provide a travel itinerary for the client upon arrival to the destination.

I have been assigned the following tasks to put the final touches on the app.

1. Retrieve Weather Data
    - generate a set of 2,000 random latitudes and longitudes
    - retrieve the nearest city
    - perform an API call with the OpenWeatherMap
    - retrieve the current weather description for each city
    - create a dataframe containing the updated weather data
    
2. Create a Travel Destinations Map
    - use input statements to retrieve customer weather preferences
    - use those preferences to identify potential travel destinations and nearby hotels
    - show those destinations on a marker layer map with pop-up markers
    
3. Create a Travel Itinerary Map. 
    - use input statements to retrieve customer destination preferences
    - use the Google Directions API to create a travel itinerary that shows the route between four cities chosen by customer
    - create a marker layer map with a pop-up marker for each city on the itinerary
    

## Resources

- Data Source: WeatherPy_Database.csv, WeatherPy_vacation.csv
- Software: Python 3.7.9, jupyter core 4.6.3, jupyter-notebook 6.1.4, qtconsole 4.7.7, ipython 7.19.0, ipykernel 5.3.4, jupyter client 6.1.7, jupyter lab 2.2.6, nbconvert 6.0.7, ipywidgets 7.5.1, nbformat 5.0.8, traitlets 5.0.5


## PlanMyTrip Summary

After generating random location coordinates and filtering the location data based upon the clients' weather preferences, I found the nearest cities and hotels for each location that matched.  Here is a snapshot of the map with pop up markers for the random locations that the client will use to select then destination.

  
![Preferred_Cities](https://raw.githubusercontent.com/ashley-green1/WeatherPY/main/Vacation_Search/WeatherPy_vacation_map.png)

Here is an example of the app's pop-up marker with city and country, hotel name and weather description for the selected vacation cities.
![PopUp_Markers](https://github.com/ashley-green1/WeatherPY/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

Lastly, here is an example of the app's Travel Itinerary with driving directions between the four selected vacation cities. 
![Travel_Itinerary](https://raw.githubusercontent.com/ashley-green1/WeatherPY/main/Vacation_Itinerary/WeatherPy_travel_map.png)

  


## WeatherPy Summary

Analysis for the PlanMyTrip project relied heavily on calling API's to retrieve large amounts of data and most importantly, visualizing the data for a simple customer facing experience.  Parsing the data from JSON files with indexing and using 'try-except' so not to exceed data limits was a rewarding challenge.  Once you get the hang of it, the possibilities of automating tasks reliant on large amounts of data are endless.

Now on to the next venture.