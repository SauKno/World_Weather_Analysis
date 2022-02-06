# World_Weather_Analysis
## Background
PlanMyTrip App is wanting to make some changes based on the recommendations of their Beta testers. This project will enhance the user interface of the PlanMyTrip app with the steps below:

1. Retreive weather data for over 500 cities across the world
2. Create a Customer Travel Destinations Map
3. Create a Travel Itinerary Map

## Resources
Data Source: citipy, gmaps, API Authentication Key, OpenWeatherMap API, Google Maps and Places API, Google Maps Directions API

Software: Python 3.9.7, Anaconda Navigator 4.10.3, Jupyter Notebook

## Results
### Retrieve Weather Data
Using the NumPy depency I generated 2,000 sets of coordinates. The Python's citipy is then called to identify the nearest cities to each coordinate combination. I then used OpenWeatherMapAPI to retreive the weather data for the identified cities. 

<img width="880" alt="Screen Shot 2022-02-06 at 1 09 23 PM" src="https://user-images.githubusercontent.com/94129215/152694929-c41c747e-9d9d-4380-a9a0-604b995eac3e.png">


### Create a customer travel destination map
Utilizing gmaps on Jupyter Notebook through my authentication key, user's weather preference inputs requests cities that meet that criteria to the Google Maps and Places API. Then, the app generates a map that meets that criteria.

<img width="1272" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/94129215/152695139-c674cc2d-e414-4592-95c1-1afdfa5969ea.png">

### Create a travel itinerary map
Using Google Maps Directions API the app is then able to generate a travel rought between the 4 cities in the order selected by the user. 

<img width="1171" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/94129215/152695379-084411ec-4b19-4590-8514-49649fb651ad.png">


