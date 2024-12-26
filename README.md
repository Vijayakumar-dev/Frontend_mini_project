# Weather App

A simple weather application built using HTML, CSS, and JavaScript. The app allows users to search for a city's current weather, including temperature, humidity, and wind speed. 

## Features

- Search for any city to get the weather information.
- Displays current temperature, humidity, and wind speed.
- Dynamic background and weather icons.
- Minimalistic and responsive design.

## Prerequisites

Before using or modifying this app, ensure you have the following:

1. **A Web Browser**: Modern browsers like Chrome, Firefox, or Edge.
2. **Internet Connection**: Required to fetch real-time weather data.
3. **Weather API Key**:
   - Sign up on a platform like [OpenWeatherMap](https://openweathermap.org/) or any preferred weather API provider.
   - Generate your API key.
   - Replace the placeholder in the `script.js` file with your API key:
     ```javascript
     const apiKey = "YOUR_API_KEY";
     ```

## Technologies Used

- **HTML5**: For the structure of the webpage.
- **CSS3**: For styling the webpage with a modern look.
- **JavaScript**: To handle user input and update weather data dynamically.

## File Structure

```plaintext
weather-app/
│
├── index.html       # The main HTML file for the weather app interface.
├── style.css        # CSS file for styling the application.
├── script.js        # JavaScript file to handle user input and display weather data.
└── images/          # Folder for storing weather-related icons (e.g., sun, rain, wind).
