# Classy Weather

Classy Weather is a React application that fetches and displays weather information for a specified location. It utilizes the Open-Meteo API for weather data and a geocoding API for location data.

## Features

- Search for weather by location.
- Display weather forecast for the next few days.
- Show weather icons based on weather codes.
- Display location name with country flag.
- Save last searched location in local storage.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/osama206/classy-weather.git
   cd classy-weather
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Start the application:
   ```bash
   npm start
   ```

## Usage

- Open the application in your browser.
- Enter a location in the search input field.
- Click on the "Get weather" button to fetch and display the weather information.

## Utility Functions

- **getWeatherIcon(wmoCode)**: Converts weather code to weather icon.
- **convertToFlag(countryCode)**: Converts country code to flag emoji.
- **formatDay(dateStr)**: Formats a date string to a short weekday name.

## Credits

- [Open-Meteo API](https://open-meteo.com/): Provides the weather data.
- [Geocoding API by Open-Meteo](https://open-meteo.com/en/docs/geocoding-api): Provides geocoding data.
- [Emoji flags](https://unicode.org/emoji/charts/full-emoji-list.html): For displaying country flags as emojis.

---
