# Weather App
The weather app allows users to enter a city name and receive current weather information, such as temperature, weather conditions, humidity, and wind speed. It uses an external weather API (like OpenWeatherMap) to retrieve this data.


## Features
- User Input: Users can enter any city name to get weather information.
- Weather Information: The app displays the current temperature, weather description, humidity, and wind speed.
- Basic Error Handling: Displays an error message if the city is not found or the input is invalid.

## Project Structure
1. HTML (index.html):
   - This is the main structure of the app.
   - It contains an input field for users to enter the city name, a button to initiate the search, and a section to display the weather results.
2. CSS (style.css):
   - This file is used to style the app and make it visually appealing.
   - It includes styles for the body, container, input fields, button, and result section.
   - The styles help center the content on the page and give the app a clean, minimalistic look.
3. JavaScript (script.js):
   - his file contains the logic for fetching weather data from the external weather API.
   - When the user clicks the "Search" button, it uses the JavaScript fetch function to send a request to the weather API.
   - The JavaScript then parses the response and dynamically displays the weather data (temperature, weather condition, humidity, and wind speed) on the page.
   - Basic error handling is also included, such as handling invalid city names.


## API Key:
- The app requires an API key from a weather service (e.g., OpenWeatherMap). To get this key, you need to sign up at OpenWeatherMap and use the provided API key in the JavaScript file.
     
   
