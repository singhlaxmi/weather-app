# simple-weather-app

## Overview
This Weather App is a simple web application that allows users to check the current weather conditions for a specific location. It uses HTML, CSS, and JavaScript for the frontend and the OpenWeatherMap API as a free weather data source.

## Features
- **Current Weather:** Get up-to-date weather information for any location.
- **Temperature:** Display the temperature in Celsius or Fahrenheit.
- **Weather Icons:** Use weather icons to visualize the current conditions.
- **City Search:** Search for weather information by entering a city name.

## Technologies Used
- HTML
- CSS
- JavaScript
- [OpenWeatherMap API](https://openweathermap.org/api)

## Configuration
To configure the app to use your own OpenWeatherMap API key, follow these steps:

1. Sign up for a free OpenWeatherMap API key on [OpenWeatherMap's website](https://openweathermap.org/api).
2. In the `js/app.js` file, replace the value of the `apiKey` variable with your API key.
   
```javascript
const apiKey = 'YOUR_API_KEY_HERE';
