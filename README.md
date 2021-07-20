# python-API-challenge

## Objective

Using API calls, get the weather from different global cities and filter on weather conditions what the ideal place for a vacation is. Present final destinations on map. 

## WeatherPY 

Retrieve approx 500 cities and information about their weather patterns including: Temperature, cloudiness, humidity and windspeed. Filter on any cities where humidity is > 100% and drop from the data frame. Create the following plots based on remainign data:

1. Latitude vs Temp
2. Latitude vs Humidity
3. Latitude vs Cloudiness 
4. Latitude vs Windspeed 

Conduct linear regression on all the graphs. 

## VacationPy 

Use the cleaned weather py csv from earlier to pull in the data. Using gmaps, configure heatmap to display humidity percentage for each city. 
Ideal conditions are defined as temperature inbetween 70 and 80 degrees, 0 cloudiness and windspeed less than 10mph. 
Call Google Places API to find hotel within 5000 meters of each city matching the above criteria. 

