
# Weather App

A simple weather application that allows users to search for current weather conditions in any city around the world using the OpenWeatherMap API.

## Features

- Displays the current temperature, humidity, and wind speed.
- Shows an icon representing the current weather conditions (clear, cloudy, rainy, etc.).
- Error message is displayed when an invalid city name is entered.

## Technologies Used

- **HTML**: Structure of the app.
- **CSS**: Styling for the user interface.
- **JavaScript**: Interactivity and API integration.
- **OpenWeatherMap API**: For fetching real-time weather data.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```

3. Open `index.html` in your preferred browser.

## Usage

1. Enter the name of a city in the input field.
2. Click the search button.
3. The app will display the weather conditions for the specified city, including temperature, humidity, and wind speed.
4. If an invalid city name is entered, an error message will be shown.

## Files

- `index.html` – Contains the HTML structure of the app.
- `style.css` – Contains the styles for the app layout and design.
- `script.js` – Handles the logic for fetching and displaying the weather data from the API.

## API Integration

This app uses the OpenWeatherMap API to fetch weather data. You will need an API key to use it. The API key is already included in the `script.js` file but should be kept secure in production environments.

## License

This project is licensed under the MIT License.
