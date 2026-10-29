# Weather App 🌤️

A desktop weather application built with PyQt5 that shows the current weather for any city. Data is fetched from the OpenWeatherMap API.

## Features

- Enter a city name to see the temperature, weather description, and a matching emoji
- Handles HTTP errors (400, 401, 404, 500, etc.) and connection errors with clear messages for the user

## Built With

- Python 3
- PyQt5
- requests
- python-dotenv

## Installation

1. Clone the repository:

       git clone https://github.com/Kaanbot23/weather-app.git
       cd weather-app

2. Install the required libraries:

       pip install PyQt5 requests python-dotenv

3. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api).

4. Create a file named `.env` in the project folder and add your key:

       API_KEY=your_api_key_here

5. Run the app:

       python weather_API_app.py

## Note

This project was created for learning purposes.

4. Open `weather_API_app.py` and replace the `api_key` value with your own key.