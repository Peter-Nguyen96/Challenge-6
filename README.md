Purpose:

Create a real-time weather tracking, and route planning program to major cities and nearby hotels for a travel agency.  Real_time weather data provided by OpenWeatherMap API and map data provided by google maps API.

To run the program, make sure to follow the steps below if using jupyter notebook.  This program will not work in VS Studio Code.
In terminal:

>conda install -c conda-forge gmaps

>pip install gmaps

>jupyter nbextension enable --py --sys-prefix gmaps

>jupyter nbextension enable --py gmaps

>python
>>import requests

launch jupyter notebook from anaconda terminal
jupyter notebook

config.py files
add the following to a config.py file and run the code, replace 'ENTER KEY' with your api key

OpenWeatherMap API key
weather_api_key="ENTER KEY"
Google API key
goo_API_key="ENTER KEY"

Place config file in main folder, Vacation_Itinerary, and Vacation_Search folder (any folder with an .ipynb jupyter notebook source code file).

