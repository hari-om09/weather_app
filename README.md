# Weather App with JavaScript

## Overview
This project is a simple and elegant Weather App built using HTML, CSS, and JavaScript. It fetches real-time weather data from the OpenWeatherMap API based on the user's input and displays the current temperature, weather description, humidity, and wind speed. The app also handles errors for invalid or non-existent locations.

## Features
- Search for weather information by city name
- Displays temperature, weather description, humidity, and wind speed
- Handles invalid locations with a user-friendly error message
- Clean and modern user interface

## Technologies Used
- HTML
- CSS (with responsive and modern design)
- JavaScript (with async/await for API calls)
- OpenWeatherMap API

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```
3. Open the `index.html` file in your preferred browser.

## Usage
1. Enter the name of the city in the input box.
2. Click the search button.
3. The weather information will be displayed if the city is found.
4. If the city is not found, an error message will appear.

## API Key
This project uses the OpenWeatherMap API. Replace the API key in the `script.js` file with your own API key:
```javascript
const api_key = "YOUR_API_KEY";
```

## License
This project is licensed under the MIT License.

