**Weather App**
Overview
This project is a simple Weather Web Application built using HTML, CSS, and JavaScript. It allows users to:

Search for weather information by location.
View current temperature, humidity, wind speed, and weather conditions.
Display weather forecasts for the next five days.
Visualize weather data using bar, doughnut, and line charts.
Navigate between a Dashboard and Tables page to see additional details.
Features
Weather Search:

Users can search for the weather by entering a city name.
Displays the current temperature, weather condition, humidity, and wind speed.
An icon representing the weather condition is displayed.
Forecast Visualization:

Weather forecasts for the next 5 days are fetched from the API and displayed using charts.
Three types of charts are available: Bar chart (for temperature), Line chart (for trends), and Doughnut chart (for weather distribution).
Tables Page:

The Tables page displays weather data in tabular form with neatly styled borders and centered temperature values.
Responsive Layout:

The layout is responsive and adjusts based on the screen size for better usability on mobile devices.
Panel with Weather Details:

A panel on the left side of the page displays current weather details like "Feels Like," "Humidity," and "Wind Speed."
The panel also contains links to navigate between the Dashboard and Tables.
File Structure
webapp.html: This file contains the main structure of the weather application, including the search bar, current weather display, and chart container.
tables.html: A separate page that displays the weather information in a tabular format.
webapp.css: The main CSS file for styling the web application.
webapp.js: The JavaScript file that handles the logic for fetching and displaying weather data and creating charts.
How It Works
1. Fetching Weather Data:
The app uses the OpenWeatherMap API to fetch current weather and forecast data for the searched city.
The testapp.js file contains the logic for making API requests using axios to retrieve this data.
API responses are then used to update the temperature, weather condition, humidity, and wind speed on the page.
2. Charts:
The app utilizes the Chart.js library to create various weather visualizations.
Three charts (Bar, Doughnut, Line) show temperature trends and weather patterns over a 5-day forecast period.
The chart container is hidden by default and is shown when forecast data is available.
3. Tables Page:
The tables.html file shows weather data in a table format. The temperature values are centered, and the entire table has black borders for clear visibility.
The table dynamically updates based on weather data fetched through JavaScript.
4. Live Server Setup:
You can use Live Server in VSCode to run the app locally and see the changes in real-time.
Live Server serves the HTML, CSS, and JS files and automatically refreshes the browser when changes are made.
5. Panel:
The side panel (on the left side) includes a quick summary of weather details such as "Feels Like" temperature, humidity, and wind.
It also contains navigation links to switch between the Dashboard and Tables page.

How to Run the Project?
To run this application locally, you'll need to follow these steps:
1-Download the project and unzip it.
2-Open the project using vs code.
3-Install liveserver extension in vs code.
4-Right click on html files and open with live server.
5-You will see the weather app in chrome.
