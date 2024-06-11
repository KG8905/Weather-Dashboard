# Weather-Dashboard
# Weather Dashboard

This Weather Dashboard allows users to search for the weather in any city or use their current location to get the weather details. It displays the current weather and a 5-day forecast.

## Features

- **City Search**: Enter a city name to fetch and display the weather details.
- **Current Location**: Use the user's current location to fetch and display the weather details.
- **Weather Details**: Display temperature, wind speed, and humidity for the current day and the next five days.

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-repository-url.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd your-repository-folder
    ```
3. **Obtain an API key from OpenWeatherMap**:
    - Sign up at [OpenWeatherMap](https://openweathermap.org/api) and get your API key.
    - Replace `YOUR_API_KEY` in the `script.js` file with your actual API key.

4. **Open `index.html` in your preferred browser**.

## Usage

- Enter a city name in the input field and click the "Search" button to get the weather details.
- Click the "Use Current Location" button to fetch the weather details for your current location.
- The last searched city is saved and its weather details are displayed when you reload the page.
