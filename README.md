# Weather App

A simple weather application that displays the current weather and 5-day forecast for any city. This project utilizes the SheCodes Weather API to fetch real-time weather data.

## Features

- Display current weather information, including:
  - City name
  - Temperature
  - Weather description
  - Humidity level
  - Wind speed
  - Time of data update
  - Weather icon representing current conditions
- Display a 5-day weather forecast, including daily high and low temperatures with corresponding weather icons.

## Technologies Used

- **JavaScript**: Core language for handling data and dynamic updates.
- **HTML/CSS**: Used for structuring and styling the weather app interface.
- **Axios**: For making HTTP requests to the SheCodes Weather API.
- **SheCodes Weather API**: Provides real-time weather data and forecasts.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Open the project folder:

   ```bash
   cd weather-app
   ```

3. Open the `index.html` file in your preferred browser to run the application.

## Usage

1. Enter the name of a city in the search bar.
2. The app will display the current weather conditions for the specified city, including temperature, humidity, wind speed, and weather description.
3. Below the current weather, the app shows a 5-day weather forecast, including maximum and minimum temperatures with weather icons.

## Example

![Weather App Example](https://link-to-screenshot-or-gif.com)

## API Key

The app uses the **SheCodes Weather API**. To use this app, you'll need to sign up at [SheCodes Weather API](https://www.shecodes.io/weather) and replace the API key in the code with your own.

In the `searchCity` and `getForecast` functions, replace the existing API key with your key:

```javascript
let apiKey = "your-api-key-here";
```

## Contributing

Feel free to fork this repository, create a new branch, and make any improvements you'd like. Pull requests are welcome!

## License

This project is open-source and available under the MIT License.
