# Weather-Journal App Project

## Overview

This project requires you to create an asynchronous web app that uses Web API and user data to dynamically update the UI.

## Setup and Dependencies

### To get the project up and running follow the steps below:

- make sure that the Node and packages (express, cors and body-parser) installed, and which are used to create the server.
- After that to start your server, run the command node server.js in your terminal
- the project works on port 3000 . we need to enter http://localhost:3000/ in the browser.

## Instructions

you can write a valid 5 digt Us Zip Code in the zip code area and write what you want in the feelings area.
Either info can be missing and the project handles that by showing the apropriate content
in the most recent area

## Important Notes

I used the starter code provided by udacity in the course content

there is a note in the rupric: The following line of code should be at the top of the app.js file: Personal API Key for OpenWeatherMap API
const apiKey = '<your_api_key>&units=imperial';
this a little bit different from the guide about the api call in the website openweathermap.org
which is http://api.openweathermap.org/data/2.5/forecast?id=524901&appid={API key}
the id was 6 digits in this example
the zip code that works in this project is 5 digits long
some examples i tested was provided in https://en.wikipedia.org/wiki/ZIP_Code like

- 02115 (Boston),
- 10001 (New York City),
- 19103 (Philadelphia),
- 21201 (Baltimore),
- 20008 (Washington, D.C.),
- 30303 (Atlanta),
- 33130 (Miami)
- 40202 (Louisville),
- 50309 (Des Moines),
- 60601 (Chicago),
- 63101 (St. Louis),
- 77036 (Houston),
- 80202 (Denver),
- 94111 (San Francisco),
- 98101 (Seattle),
- and 99950 (Ketchikan, Alaska) (the highest ZIP Code)

  all these values in the US works in the app.

The project gives the temperature in fahrenheit

This is my apiKey = **"fc613da10931af54bccdc98e5aa60654&units=imperial"**

the project handles white spaces before and after the data entry by the user
