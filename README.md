# Weather App

A simple and responsive Weather App built using **HTML**, **CSS**, and **JavaScript**. This application fetches real-time weather data from the OpenWeatherMap API and displays current weather conditions for any city entered by the user.

## Features

* Search weather by city name
* Displays:

  * Temperature (°C)
  * Humidity (%)
  * Wind Speed (km/h)
* Dynamic weather icons based on current conditions
* Error handling for invalid city names
* Responsive user interface

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* OpenWeatherMap API

## Screenshots

### Weather Information

* Temperature
* City Name
* Humidity
* Wind Speed
* Weather Condition Icon

## Project Structure

```
weather-app/
│
├── index.html
├── style.css
├── images/
│   ├── clear.png
│   ├── clouds.png
│   ├── drizzle.png
│   ├── humidity.png
│   ├── mist.png
│   ├── rain.png
│   ├── search.png
│   └── wind.png
└── README.md
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/weather-app.git
```

2. Navigate to the project directory:

```bash
cd weather-app
```

3. Open `index.html` in your browser.

## API Setup

This project uses the OpenWeatherMap API.

1. Create a free account at OpenWeatherMap.
2. Generate an API key.
3. Replace the API key in `index.html`:

```javascript
const apiKey = "YOUR_API_KEY";
```

## How It Works

1. User enters a city name.
2. JavaScript sends a request to the OpenWeatherMap API.
3. Weather data is retrieved and displayed on the page.
4. The weather icon changes automatically according to the current weather condition.
5. If the city name is invalid, an error message is shown.

## Future Improvements

* Display 5-day weather forecast
* Add loading spinner
* Search by current location
* Dark/Light mode
* Support for Fahrenheit and Celsius
* Press Enter to search

## Author

Nizam Nizami

## License

This project is open-source and available under the MIT License.
