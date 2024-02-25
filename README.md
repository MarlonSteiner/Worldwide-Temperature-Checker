# Weather Temperature Fetcher

This Python script fetches and displays the current temperature of a given city using the wttr.in service.

## Requirements

- Python 3.x

## Usage

1. Clone the repository to your local machine:

`git clone https://github.com/your-username/weather-temperature-fetcher.git`

2. Navigate to the repository directory:
cd weather-temperature-fetcher

3. Run the script:
 python weather_temperature_fetcher.py

4. Enter the name of the city when prompted.

5. The script will fetch and display the current temperature of the specified city.
   example - City: London 7°C

## How It Works

The script utilizes the urllib.request module to make a GET request to wttr.in with the specified city.
The temperature is extracted from the response using the provided URL format (?format=%t).
The temperature is then printed to the console.

   
