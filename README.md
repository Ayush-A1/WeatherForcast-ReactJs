# React Weather App

A simple weather application built with React and Redux, utilizing the OpenWeatherMap API to provide current weather details and a 5-day forecast for different cities.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- Real-time current weather details.
- 5-day forecast with temperature, weather description, and icons.
- Toggle between Celsius and Fahrenheit units.
- Responsive design for a seamless user experience.

## Prerequisites
- Node.js and npm installed on your machine.
- OpenWeatherMap API key. [Get it here](https://openweathermap.org/appid).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/react-weather-app.git
Change into the project directory:
bash  "cd react-weather-app"
Install dependencies:
bash  - "npm install"
 ##Configuration
   1. Obtain an API key from OpenWeatherMap.
   2.Create a config.js file in the src/config directory.
   3.Add the following content to config.js:
javascript:
"export const hostName = "https://api.openweathermap.org";
export const appId = "YOUR_OPENWEATHERMAP_API_KEY";"
Usage
Start the development server:
bash-"npm start"
Open your browser and visit http://localhost:3000.
Project Information
This project is created using Vite and Create React App. The weather app displays current weather details and the next 5 days' forecast for different cities and countries. It consumes data from the OpenWeatherMap API.

This website can be used to get weather forecasts for various cities and countries.

Contributing
Feel free to contribute by opening issues and submitting pull requests.