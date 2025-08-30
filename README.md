# Power BI Weather Dashboard

A comprehensive and dynamic weather dashboard built in Microsoft Power BI. This project is designed to provide real-time weather data, multi-day forecasts, and air quality information for selected cities in a visually appealing and easy-to-understand interface.

![Dashboard Screenshot](<dashboard screenshot>)

---

## About The Project

This dashboard leverages a live weather API to fetch and display up-to-date meteorological data. The report is fully interactive, allowing users to seamlessly switch between different locations to get specific local forecasts. It was built from the ground up, focusing on clean data transformation in Power Query, robust calculations using DAX, and a modern, intuitive UI design.

---

## Key Features

* ☀️ **Current Weather Overview:** Displays real-time temperature, conditions (e.g., "Cool"), and the last updated timestamp.
* 📍 **Multi-City Selector:** Interactively switch between forecasts for different locations using a slicer.
* 📊 **Detailed Metrics:** Individual cards for **Humidity**, **Wind Speed**, **Visibility**, **Pressure**, **UV Index**, and **Precipitation**.
* 📈 **7-Day Forecast:** A line chart showing temperature trends for the upcoming week.
* 🌅 **Sunrise & Sunset Times:** Clearly displayed for the current day.
* 💨 **Air Quality Index (AQI):** A radial gauge showing the current AQI level (e.g., "Moderate") with a breakdown of key pollutants (PM2.5, PM10, O3, etc.).
* 💧 **Chance of Rain:** A bar chart visualizing the probability of precipitation for each day of the forecast.

---

## Built With

This project was created using the following tools and technologies:

* **[Microsoft Power BI](https://powerbi.microsoft.com/)** - The core tool for data modeling, analysis, and visualization.
* **[Power Query (M Language)](https://docs.microsoft.com/en-us/powerquery-m/)** - For connecting to the API and transforming the raw JSON data.
* **[DAX (Data Analysis Expressions)](https://docs.microsoft.com/en-us/dax/)** - For creating calculated columns and measures.
* **[WeatherAPI.com](https://www.weatherapi.com/)** - The source of the live weather and forecast data.

---

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* **Power BI Desktop** installed.
* A free **API key** from [WeatherAPI.com](https://www.weatherapi.com/) or a similar weather data provider.

### Setup

1.  Clone the repository or download the `.pbix` file.
2.  Open the project in Power BI Desktop.
3.  Go to **Transform data** -> **Edit parameters**.
4.  Enter your personal API key into the `pApiKey` parameter.
5.  Click **Close & Apply** and refresh the report.
