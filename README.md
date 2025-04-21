# Weather App

A simple and elegant weather application that provides real-time weather information for any city worldwide.

## Features

- Search weather by city name
- Display current temperature in Celsius
- Show humidity percentage
- Display wind speed
- Dynamic weather icons based on conditions
- Responsive design
- Error handling for invalid city names

## Technologies Used

- HTML5
- CSS3
- JavaScript
- OpenWeatherMap API

## Setup

1. Clone this repository
2. Create a `config.js` file in the root directory
3. Sign up at [OpenWeatherMap](https://openweathermap.org/) to get your API key
4. Add the following to your `config.js`:
   ```javascript
   const apiKey = "YOUR_API_KEY_HERE";
   ```
5. Open `index.html` in your browser

## Usage

1. Enter a city name in the search box
2. Click the search button or press Enter
3. View the current weather conditions including:
   - Temperature
   - Humidity
   - Wind Speed
   - Weather condition icon

## Screenshots

The app includes visual representations for different weather conditions:

- Clear weather
- Cloudy conditions
- Rain
- Drizzle
- Mist/Fog

## Project Structure

```
├── index.html          # Main HTML file
├── style.css          # Stylesheet
├── script.js          # Main JavaScript file
├── config.js          # API key configuration (not included in repo)
└── images/            # Weather icons and UI elements
```

## Note

Make sure to keep your API key private and never commit the `config.js` file to version control.
