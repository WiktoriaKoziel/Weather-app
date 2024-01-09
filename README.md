# Weathee
![Screenshot from the web app](/screenshots/1600x1200.png)
## Introduction

Weatheee is a web application that provides real-time weather information. It offers features such as viewing the current weather, a 5-day forecast, wind speed, temperature for the current day, sunrise and sunset times, air quality, humidity, visibility, feels like temperature, and atmospheric pressure.

The application is developed using HTML, CSS, and JavaScript, and it utilizes the OpenWeather API to fetch weather data for different cities around the world.

You can view the whole application HERE 

## Table of Contents

- [Overview](#overview)
- [Initial Setup](#initial-setup)
  - [Requirements](#requirements)
- [Structure](#structure)
- [HTML](#html)
  - [index.html](#index-html)
- [CSS](#css)
  - [style.css](#style-css)
- [JavaScript](#javascript)
  - [api.js](#api-js)
  - [module.js](#module-js)
  - [app.js](#app-js)
  - [route.js](#route-js)
- [Features](#features)
- [Screenshots](#screenshots)
- [Participation](#participation)
- [License](#license)

## Overview

The Weathee Website delivers live atmospheric data straight to your screen. With this web app, you can stay ahead of the weather with real-time updates, comprehensive forecasts for the week ahead, velocity of wind, daily temperature fluctuations, dawn and dusk timings, plus insights into air purity, moisture levels, visibility range, apparent temperature, and barometric pressure.

### Key Features:

- View current weather conditions (temperature, weather icon, and description).
- Get a 5-day weather forecast.
- Display wind speed and temperature every 2 hours for the current day.
- Show sunrise and sunset times for the selected city.
- Provide information about air quality, humidity, visibility, feels like temperature, and atmospheric pressure.

## Initial setup

### Requirements

A stable internet connection is vital to access real-time data from the OpenWeather API.

## Structure

Weathee codebase is neatly partitioned for clarity and maintainability:

- `index.html`: The main HTML of the user interface.
- `style.css`: The stylesheet that defines the app's aesthetic.
- `api.js`: The script to the OpenWeather API's resources.
- `module.js`: A toolkit for weather-related data manipulation.
- `app.js`: The core of the application's functionality.
- `route.js`: The navigator for app routing and URL management.

## HTML

### index.html

This is main HTML -  the structural design of Weathee. Here, you'll find the blueprint of the user interface, including a search section, live weather display, forecast panel, and detailed atmospheric conditions, all packaged in a layout that's responsive to any device.

## CSS

### styles.css

Styles.css is the canvas where Weathee visual experience is painted. It creates the design system—color schemes, typographic scale, layout grids—ensuring a consistent and accessible user experience. The CSS is organized using class selectors for specific components and follows a mobile-first approach with media queries for responsive design.

## JavaScript

### api.js

The api.js file contains functions to interact with the OpenWeather API. It includes functions to fetch weather data based on city names and coordinates using asynchronous JavaScript (async/await) and the Fetch API. The API key required for accessing the OpenWeather API is stored as a constant.

### module.js

The utility belt of Weathee, module.js, is where data gets transformed. Temperature unit conversions and wind speed calculations all happen here.

### app.js

app.js is the app's interactivity. It defines functions to update the weather information on the user interface based on the data fetched from the API.

### route.js

route.js is the traffic controller for Weathee routes, managing URL changes and ensuring users always land on the right view.

## Features

- Search for city-specific weather updates.
- Real-time data procurement from the OpenWeather API.
- Display the temperature, weather icon, and summaries for current conditions.
- A forecast that extends into a 5-day weather narrative.
- An hourly forecast with wind speed and temperature metrics.
- Display of sunrise and sunset times by city.
- Extra weather intelligence: air quality, humidity, visibility, thermal sensation, and pressure.
- A responsive interface suits on any device.
  
## Screenshots

### Iphone SE

![Screenshot from the web app iphone se](/screenshots/iphonese1.png)
![Screenshot from the web app iphone se](/screenshots/iphonese2.png)
![Screenshot from the web app iphone se](/screenshots/iphonese3.png)

### Ipad mini

![Screenshot from the web app ipad mini](/screenshots/ipadmini1.png)
![Screenshot from the web app ipad mini](/screenshots/ipadmini2.png)

### Ipad pro

![Screenshot from the web app ipad pro](/screenshots/ipadpro.png)

### 1024x768 Resolution

![Screenshot from the web app 1024x768 Resolution](/screenshots/1024x7681.png)
![Screenshot from the web app 1024x768 Resolution](/screenshots/1024x7682.png)

### 1280x1024 Resolution

![Screenshot from the web app 1280x1024 Resolution](/screenshots/1280x10241.png)
![Screenshot from the web app 1280x1024 Resolution](/screenshots/1280x10242.png)

### 1600x1200 Resolution

![Screenshot from the web app 1600x1200 Resolution](/screenshots/1600x1200.png)

## Participation

We welcome contributions to enhance the project! Encounter a glitch? Have a feature in mind? Share it via GitHub issues. Your pull requests are the winds that propel this project forward.

## License

This project is distributed under the GNU General Public License (GPL). You can find the full text of the license in the [LICENSE](LICENSE.txt) file.
The project was done with the help of codewithsadee [tutorial](https://www.youtube.com/watch?v=QMwyNnjAils)  this was his idea and this project is inspired by him. 
