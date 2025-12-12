
🌦️ ️#Weather Analysis Dashboard using Power BI
A visually rich and fully interactive **Weather & Air Quality Dashboard** built using **Power BI** and real-time data from **WeatherAPI.com.**
This project visualizes current weather conditions, hourly & daily forecasts, air quality indicators, sunrise & sunset times, and rain probability for multiple locations.

📘 About the Project

This Power BI dashboard fetches **real-time and forecasted weather data** using WeatherAPI. The main goal of this project is to provide a **clean, modern, dark-themed interface** to monitor weather and air quality conditions for any city.

The dashboard helps users analyze:

• Temperature & weather conditions

• Air Quality Index (AQI)

• Sunrise & sunset timings

• Hourly and daily forecasts

• Rain probability

• Wind, humidity, pressure, visibility, UV index, and more

The project uses a parameterized API endpoint, allowing easy city-level customization.

##⭐ Features
###🌀 Current Weather Panel

• Current temperature (°C)

• Real-time weather condition (Mist, Cloudy, Sunny, etc.)

• Last updated timestamp

• Quick location switching

##📈 Forecast Section

• 7-day weather forecast

• Smooth temperature trend line

• Day-by-day average temperature values

##🌅 Sunrise & Sunset

• Clean card layout with icons

• Automatically updated times per city

##🌧️ Chance of Rain

• Daily rain probability indicators

• Percentage comparison across days

##🫁 Air Quality Index (AQI)

• PM10

• PM2.5

• SO₂

• NO₂

• O₃

• CO

• Circular AQI gauge with color-coded health indicators

##🌐 Data Source

This project uses the WeatherAPI Forecast Endpoint:
(http://api.weatherapi.com/v1/forecast.json?key=YOUR_API_KEY&q={CITY_NAME}&days=7&aqi=yes&alerts=no)

Parameters Explained
Parameter :-	Description
key       :-  Personal WeatherAPI key (keep private)
q	        :-  City name or coordinates
days      :-	Number of forecast days (7 used)
aqi       :-	Includes air quality data
alerts    :-	Weather alerts (disabled)

##🧩 Data Model

The data model is designed using Power BI **Model View**:

• Locations (1) → (*) Current

• Locations (1) → (*) Forecast_Days

• Locations (1) → (*) Forecast_Hours

A central **Locations** table enables accurate filtering and efficient DAX calculations across all visuals.

##📥 Installation & Setup
###Requirements

• Power BI Desktop (latest version)

• WeatherAPI account (free tier)

###Steps

1. Clone the repository
 git clone https://github.com/your-username/weather-powerbi-dashboard.git

2. Open the .pbix file in Power BI Desktop

3. Go to **Transform Data → Parameters → API_Key**

4. Paste your WeatherAPI key

5. Click **Refresh** to load data

##🚀 How to Use

• Select a city (Bangalore, Pune, Chennai, Hyderabad, etc.)

• Dashboard updates automatically:

  • Current weather

  • Hourly & daily forecast

  • AQI metrics

• Hover over charts for detailed insights

##🖥️ Dashboard Overview

• Modern dark theme with neon highlights

• Glass-style KPI cards

• Responsive and clean layout

• Multiple insight panels for weather & AQI

##📸 Screenshots
Main Dashboard View




Power BI Report View




Data Model View
