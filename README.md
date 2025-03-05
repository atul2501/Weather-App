# Weather-App
This is a simple command-line Python application that fetches the current weather details for a given city using the WeatherAPI and reads out the details using the system's text-to-speech functionality (`say` command).

## Features:
- Fetches current weather data for any city.
- Provides details such as:
  - City name
  - Temperature in Celsius
  - Last update time
  - Wind speed in kilometers per hour (kph)
  - Humidity percentage
- Uses the system's text-to-speech (`say`) functionality to read out weather details.
- Exits the program gracefully when the user inputs "q" for the city name.

## Requirements:

- Python 3.x
- Internet connection (to fetch weather data)
- `requests` library (to send HTTP requests)
- `json` library (to parse the API response)
- `os` library (to use system commands like `say`)

## How to Run:

1. Clone this repository or download the code.
2. Install the `requests` module if you don't have it:
   ```bash
   pip install requests
