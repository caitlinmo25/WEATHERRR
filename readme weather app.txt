## Features

- **Location-based Weather Forecast**: Users can enter any US location to get a detailed 7-day weather forecast.
- **Daily Forecast Display**: The website displays the date, temperature (in Celsius), and weather description for each day in the forecast period.
- **Error Handling**: Informative error messages are shown if the user does not enter a location or if weather data cannot be fetched.

These features were selected to provide a straightforward and functional experience for obtaining weather forecasts. The emphasis was on simplicity, usability, and effective presentation of weather data.

## Technology Stack

- **Frontend**: HTML, CSS (with templates served by Flask)
- **Backend**: Python, Flask
- **APIs**: OpenWeatherMap API for weather data

## Getting Started

To run WeatherApp locally:

1. Ensure you have Python installed on your machine.
2. Clone this repository to your local machine.
3. Install dependencies by running `pip install -r requirements.txt`.
4. Run `app.py` using the command `python app.py`.
5. Access the web application at `http://127.0.0.1:5000/`.

## Usage

1. Open the website.
2. You will be greeted with a simple form asking for a location.
3. Enter a US location (e.g., "New York") and submit.
4. View the 7-day weather forecast displayed in a table format.

## Testing

Tests are located in the `tests` directory. To run tests, use the command `pytest` from the root directory of the project. Ensure you have pytest installed (`pip install pytest`).

## About the OpenWeatherMap API

We chose the OpenWeatherMap API for its reliability, extensive documentation, and ease of use. It provides detailed weather forecasts, which include temperature, weather conditions, and timestamps, enabling our application to deliver accurate and timely weather information. For more information about the API, visit [OpenWeatherMap's official documentation](https://openweathermap.org/api).

## Contributions and Feedback

We welcome contributions and feedback on our project. Please feel free to open an issue or pull request on GitHub if you have suggestions or improvements.