# Weather Now - Air Quality by Zip Code

This Python project fetches real-time air quality data from the AirNow API based on a provided zip code. The user interface is created using Tkinter, allowing users to input a zip code and retrieve current air quality information.

## Overview

The application aims to provide users with current air quality information based on a specified zip code. It fetches data from the AirNowAPI, displaying the city, air quality index (AQI), and the current air quality category (e.g., Good, Moderate, Unhealthy, etc.).

The background color of the interface dynamically changes based on the air quality category:

- **Good**: Green background
- **Moderate**: Yellow background
- **Unhealthy for Sensitive Groups**: Orange background
- **Unhealthy**: Red background
- **Very Unhealthy**: Purple background
- **Hazardous**: Maroon background

## Usage

1. Clone the repository.
2. Ensure Python is installed.
3. Install required libraries: `tkinter`, `PIL`, `requests`.
4. Run the Python script.
5. Enter a valid zip code and click "Lookup Zipcode" to retrieve the air quality information.

## Technologies Used

- **Python**: Core language for the application.
- **Tkinter**: Used to build the graphical user interface (GUI).
- **PIL (Pillow)**: For image handling and manipulation.
- **Requests**: Library for making HTTP requests to the AirNow API.
