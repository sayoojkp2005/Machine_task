# Weather App

A simple and responsive weather application built with HTML, CSS, and JavaScript. The app lets users search for a city and view real-time weather information such as temperature, humidity, wind speed, and a matching weather icon.

## Features

- Search for any city worldwide
- Display current temperature in Celsius
- Show humidity and wind speed
- Update weather icons based on conditions like clouds, rain, snow, mist, and clear sky
- Clean and modern glassmorphism-inspired user interface
- Responsive design for desktop and mobile screens

## Tech Stack

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Project Structure

- `weather.html` — main app interface
- `weather.css` — styling and layout
- `images/` — icons and background assets

## How It Works

The app uses the OpenWeatherMap API to fetch the current weather data for the city entered by the user. The JavaScript code updates the DOM with the response data and changes the icon to match the weather condition.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/sayoojkp2005/Machine_task.git
   ```
2. Open the project folder.
3. Start a local web server:
   ```bash
   python -m http.server 8000
   ```
4. Open your browser and visit:
   ```text
   http://localhost:8000/weather.html
   ```

## API Key

This project uses an OpenWeatherMap API key. The current JavaScript file contains a key that is already included in the project, but for long-term use you may want to replace it with your own API key from the OpenWeatherMap website.

## Notes

- The app works best when run via a local web server.
- Network access is required to fetch live weather data.

## License

This project is for educational/demo purposes.
