# weather-server-side-API

A weather dashboard that will run in the browser and feature dynamically updated HTML and CSS.
The OpenWeather One Call API is used to retrieve weather data for cities.

Link to deployed applicaton:
http://vianvianc.github.io/weather-server-side-API

Website mockup:
![mockup](assets/images/weather.png)

GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index
WHEN I view the UV index
THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, the wind speed, and the humidity
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city
