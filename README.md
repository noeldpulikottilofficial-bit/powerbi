# powerbi
​🌦️ Real-Time Global Weather Dashboard
​Power BI | Weather API Integration | Data Visualization
​📌 Project Overview
​This project is a dynamic Power BI Dashboard that connects directly to a live Weather API to provide real-time atmospheric insights. Unlike static reports, this dashboard uses API authentication to fetch the latest weather data for any given location at the click of a button.
​The goal was to move beyond traditional Excel datasets and master Web Data Connectors and JSON transformation in Power Query.

​🚀 Key Features

​Live API Integration: Automated data fetching using REST API (OpenWeatherMap/WeatherAPI).
​Real-Time Metrics: Tracks Temperature (High/Low), Humidity, Visibility, UV Index, and Wind Speed.
​Dynamic UI: Dark-themed, high-contrast interface designed for "At-a-glance" monitoring.
​Interactive Slicers: Filter data by City or Region to see localized updates instantly.
​Advanced DAX: Custom measures for unit conversions and time-intelligence.

​🛠️ Tech Stack & Skills

​Tool: Power BI Desktop
​Data Source: Weather API (JSON Format)
​Power Query (M): Used for flattening nested JSON records, handling API authentication, and data type transformation.
​DAX: Implemented for dynamic KPIs and custom formatting.
​UI/UX: Custom icon integration and dark-mode aesthetic.

​📖 How it Works (Technical Deep Dive)

​1. Data Acquisition
​I utilized the Web.Contents function in Power Query to connect to the API endpoint.
2. Data Cleaning
​The raw API response was a nested JSON object. I performed the following:
​Expanded record columns to extract current and location data.
​Converted Unix timestamps into readable Date/Time formats.
​Renamed columns for better end-user readability.

​📊 Dashboard Insights

​Atmospheric Health: Monitoring the relationship between Humidity and Visibility.
​Forecast: forecast of the upcoming days.
​Wind Patterns: Real-time wind speed tracking in km/h.
