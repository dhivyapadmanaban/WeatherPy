# WeatherPy

## Project Overview
Enhancing PlanMyTrip app which allows travelers to filter the data based on their preferred travel criteria. Based on travelers filteration criteria PlanMyTrip app will recommend Hotel info for their trip. In this project we are collecting the data, perform exploratory analysis and visualize travel data for the customers. 

## Resources
- Data source : WeatherPy_Database.csv
- Software : Pandas, Jupyter notebook , APIs

## Weather_Database
Using numpy function, create random numbers to determine latitude and longitude to generate set of cities. Using Openweathermap API, fetch below information for the latitude / longitude combination and create dataframe. 
- Latitude and Longitude
- Maximum temperature
- Humidity , cloudiness and Wind speed.
- City and country name
- Weather description.

Finally copy the dataframe and export to WeatherPy_Database.csv file. Sample data of dataframe below.

![image](https://user-images.githubusercontent.com/83181834/120942672-5cb05a00-c6df-11eb-88c4-d57d5487c5a0.png)

## Vacation_Search
Prompting users to enter temperature range for their planned trip and create new dataframe for preferred cities. Using googleAPIs nearbysearch, find Hotel name for the filtered latitude/longitude combinations. Create google maps using the new dataframe and add markers to help travelers choose their destinations.

![image](https://user-images.githubusercontent.com/83181834/120942969-f7f5ff00-c6e0-11eb-990a-dcd8acb8189d.png)

## Vacation_Itinerary

Create sample vacation itinerary by picking random cities , finding latitude/longitude co-ordinates and creating google maps for the round trip.

![image](https://user-images.githubusercontent.com/83181834/120943058-7a7ebe80-c6e1-11eb-9c6a-b2bcb52257d2.png)

Creating new dataframe for above vacation itenary. Generate google heatmap with markers with all relevent information. 

![image](https://user-images.githubusercontent.com/83181834/120943146-f7119d00-c6e1-11eb-9ff7-28615397172d.png)





