# blomma-reloaded

SEE IT LIVE: https://blommadev.fi/
EXPERIMENTAL VERSION: https://blommadev.fi/index-beta.html

replaces old WeatherWebApp

This project aims to create a minimalistic monospace styled webpage for my projects.

made for learning purposes of JS, HTML and CSS
part of bigger upcoming project for building a weather station at home
dinosaur picture :)
ability to change lang of pulled data* (read more at optional)
See it live here: https://blommadev.fi/index-legacy.html

Features:

Fetching weather data from OpenWeatherMap with City name or client location
displaying the data on the webpage
Requirements:

OpenWeatherMap API token
webserver / localhost
Optional:
by removing all "lang=fi" in "const base" (file: script.js) you can pull the weather data in English.
in index.html you can find text for the desc, if you can figure out the Finnish translations it is possible to change the desc.
Usage:

create config.js file in root path and enter the code below along with your OpenWeatherMap API key in API_KEY var
const config = { API_KEY : 'yourOpenWeatherMapAPIkey', }
