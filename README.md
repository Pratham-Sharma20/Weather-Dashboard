🌤️ Weather Dashboard

A modern, responsive Weather Dashboard that provides real-time weather information, hourly forecasts, and a 7-day forecast for any city worldwide. Built using HTML, CSS, and Vanilla JavaScript, and powered by the Open-Meteo API (no API key required).

🚀 Features

🔍 City-based search for weather information

🌡️ Current weather details

Temperature

Feels-like temperature

Weather condition

Humidity

Wind speed

Pressure

⏰ 24-hour hourly forecast

📅 7-day weather forecast

🎨 Modern UI with gradient background and card-based layout

⚡ Fast & lightweight (no frameworks or libraries)

🌍 Timezone-aware weather data

❌ Graceful error handling for invalid city names

🛠️ Tech Stack

HTML5 – Structure

CSS3 – Styling & responsive layout

JavaScript (ES6+) – Logic & API handling

Open-Meteo API

Geocoding API

Weather Forecast API

📦 APIs Used

Geocoding API
Converts city names into latitude & longitude

https://geocoding-api.open-meteo.com


Weather Forecast API
Fetches current, hourly, and daily weather data

https://api.open-meteo.com


✅ No API key required.

📂 Project Structure
weather-dashboard/
│
├── index.html        # Complete Weather Dashboard (HTML, CSS, JS)
└── README.md         # Project documentation

▶️ How to Run the Project

Download or clone the repository

git clone https://github.com/your-username/weather-dashboard.git


Open index.html directly in your browser
(No server or build step required)

Enter a city name and click Search or press Enter

🧠 How It Works (High-Level)

User enters a city name

City name → latitude & longitude using Geocoding API

Coordinates → weather data using Forecast API

UI updates dynamically:

Current weather

Hourly forecast (next 24 hours)

7-day forecast

🎯 Possible Enhancements

🌙 Dark / Light mode toggle

📍 Auto-detect user location

🌡️ Celsius ↔ Fahrenheit switch

📱 Progressive Web App (PWA) support

🎞️ Animations using GSAP / Framer Motion

🗺️ Weather maps integration

🧑‍💻 Author

Pratham Sharma
B.Tech CSE Student | Full-Stack Developer
