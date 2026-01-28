# 🌦️ Live Weather Monitoring Dashboard (Power BI)

An interactive **live weather analytics dashboard** built using **Power BI** and **WeatherAPI.com**, designed to visualize real-time weather conditions, air quality, and short-term forecasts across multiple cities.

This project demonstrates end-to-end data analytics skills using **API-based data ingestion**, **Power Query transformations**, **data modeling**, and **dashboard visualization** — making it well-suited for **data analyst interview portfolios**.

---

## 📌 Project Overview

Unlike traditional dashboard projects that rely on static CSV files, this dashboard connects directly to a **Weather API** to fetch live data.  
The project focuses on converting raw API responses into structured analytical tables and presenting them through clean, intuitive visuals.

The dashboard enables users to:
- Monitor current weather conditions
- Analyze air quality metrics
- Explore daily and hourly weather forecasts
- Compare weather data across multiple cities

---

## 🛠️ Tech Stack

- **Power BI** – Data modeling, Power Query, DAX, and visualization
- **WeatherAPI.com** – Real-time weather and forecast data via REST API

---

## 🔌 Data Source (API)

- **API Provider:** WeatherAPI.com  
- **Data Retrieved:**
  - Current weather conditions
  - Air Quality Index (AQI)
  - Daily forecast data
  - Hourly forecast data
- **Access Method:** API URL connected directly through Power BI

This approach enables **live or refreshable reporting** without manual file uploads.

---

## 🔄 Data Preparation (Power Query)

Key Power Query steps include:

- Connecting Power BI to the Weather API endpoint
- Parsing nested JSON responses
- Extracting current, daily, and hourly forecast data
- Handling multiple cities by duplicating and parameterizing API queries
- Merging city-level data into a consolidated master table
- Cleaning and shaping data for analytical use

---

## 🗂️ Data Model

The dashboard uses a structured and relational data model consisting of:

- **Location Table** – City and geographic metadata  
- **Current Weather Table** – Live temperature, wind, humidity, visibility, pressure, UV index  
- **Daily Forecast Table** – Day-wise forecasts, temperatures, precipitation probability  
- **Hourly Forecast Table** – Hourly weather trends  

Relationships are defined to support efficient filtering and drill-down analysis, while unnecessary intermediate tables are hidden for a clean model view.

---

## 📊 Dashboard Features & Visualizations

### 🌡️ Current Weather Overview
- Temperature with weather icons
- Location details
- Visibility, wind speed, humidity, pressure, UV index

### 🌫️ Air Quality Index (AQI)
- Overall AQI score
- Pollutant-level analysis:
  - PM2.5
  - PM10
  - CO
  - NO₂
  - SO₂
  - O₃
- Health impact indicators using color-coded visuals

### 📅 Forecast Analysis
- Daily weather forecast with icons
- Temperature trends using line charts
- Rain probability by day
- Sunrise and sunset timings

### 📍 Interactivity
- City slicer for multi-location analysis
- Custom themes and background images
- Clean, card-based UI optimized for non-technical users

---

