# WeatherBot
This is a simple Telegram bot that retrieves current weather information using the Weatherstack API. It allows users to send a location as a message, and the bot will respond with the current temperature in Fahrenheit and a brief description of the weather.

## Prerequisites
Before running this bot, make sure you have the following:

-Python 3 installed
- telepot library installed (pip install telepot)
- requests library installed (pip install requests)
- Weatherstack API key (Weatherstack website)
## Installation
1. Clone this repository to your local machine or download the source code.
2. Open the file weatherbot.py in a text editor.
3. Replace 'API_KEY' with your actual Weatherstack API key.
4. Replace 'API_KEY' with your actual Telegram bot token.
5. Save the file.
## Usage
1. Run the weatherbot.py script using Python.
python weatherbot.py
2. Start a conversation with your Telegram bot.
3. Send a location (e.g., city name, zip code) as a message to the bot.
4. The bot will retrieve the current weather information for the provided location and respond with a message containing the temperature in Fahrenheit and a weather description.
## Example
User: London
WeatherBot: Current weather in London: 70.34°F, Partly cloudy
