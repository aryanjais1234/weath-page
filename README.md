# Weather App

This is a simple weather app that allows users to check the weather for a given city. It fetches weather data from the OpenWeatherMap API.

## JavaScript Explanation
document.querySelector: This method is used to select and return the first element that matches a specified CSS selector. In the code, it is used to select various HTML elements and update their content dynamically.


## JavaScript Function Explanation

The JavaScript code in this app includes the following functions:

checkWeather(city): This function takes a city name as a parameter, fetches weather data for that city from the OpenWeatherMap API, and updates the UI with the fetched data.

Event Listener (searchBtn.addEventListener): Listens for a click event on the search button and calls the checkWeather function with the value entered in the search box.



### How API Data Fetching Works

The `checkWeather` function uses the `fetch` API to make an asynchronous request to the OpenWeatherMap API. It then parses the JSON response and updates the UI elements with the fetched data.

## How to Use

1. Open the HTML file in a web browser.
2. Enter the desired city name in the search bar.
3. Click the search button to fetch and display the weather information.

## Snapshots

<!-- Add snapshots or screenshots of the app here -->
- [Snapshot 1]('/images/web.png')
