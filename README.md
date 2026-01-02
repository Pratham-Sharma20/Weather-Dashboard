# Weather Dashboard 🌤️

A modern, responsive Weather Dashboard that provides real-time weather information, an hourly forecast (next 24 hours), and a 7-day forecast for any city worldwide. Built with plain HTML, CSS and vanilla JavaScript — no frameworks or API keys required.

---

## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [APIs Used](#apis-used)
- [Project Structure](#project-structure)
- [Installation & Usage](#installation--usage)
- [How It Works](#how-it-works)
- [Possible Enhancements](#possible-enhancements)
- [Contributing](#contributing)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

---

## Demo
Open `index.html` in your browser to run the dashboard locally.

(If you add screenshots or a hosted demo, include them here — e.g. a GIF or image under `assets/` and a link to a live demo.)

---

## Features
- 🔍 Search weather by city name
- 🌡️ Current weather details: temperature, feels-like, condition, humidity, wind speed, pressure
- ⏰ 24-hour hourly forecast
- 📅 7-day forecast
- 🌍 Timezone-aware weather data
- 🎨 Modern UI with gradient background and card-based layout
- ⚡ Fast & lightweight — no frameworks or build steps
- ❌ Graceful error handling for invalid city names

---

## Tech Stack
- HTML5 — Structure
- CSS3 — Styling & responsive layout
- JavaScript (ES6+) — Application logic & API handling

---

## APIs Used
- Geocoding API (Open-Meteo) — convert city name to latitude & longitude  
  https://geocoding-api.open-meteo.com

- Weather Forecast API (Open-Meteo) — current, hourly, and daily weather data  
  https://api.open-meteo.com

No API key required.

---

## Project Structure
```
weather-dashboard/
│
├── index.html        # Web app (HTML, CSS, JS)
├── css/              # Optional: stylesheet(s)
├── js/               # Optional: JavaScript files
├── assets/           # Optional: images/icons/screenshots
└── README.md         # Project documentation
```

> Note: Your repository layout may vary; update this section to match actual folders/files in your repo.

---

## Installation & Usage

1. Clone the repository
   ```bash
   git clone https://github.com/Pratham-Sharma20/Weather-Dashboard.git
   ```

2. Open the project
   - Option A (recommended): Serve with a simple static server (helps avoid CORS or file:// quirks)
     ```bash
     # using Python 3 (from project root)
     python -m http.server 8000
     # then open http://localhost:8000 in your browser
     ```

   - Option B: Open `index.html` directly in your browser (double-click or `open index.html`).

3. Use
   - Enter a city name, hit Enter or click Search.
   - The dashboard will show current weather, hourly forecast for the next 24 hours, and a 7-day outlook.

---

## How It Works (High-Level)
1. User enters a city name in the search bar.
2. The app calls the Geocoding API to get latitude and longitude.
3. Those coordinates are used to query the Forecast API for current, hourly and daily weather data.
4. UI updates dynamically to present current weather, hourly cards, and daily forecast cards.

---

## Possible Enhancements
- 🌙 Dark / Light mode toggle
- 📍 Auto-detect user location via browser geolocation
- 🌡️ Celsius ↔ Fahrenheit toggle
- 📱 Progressive Web App (PWA) support — installable, offline caching
- 🎞️ Add animations (GSAP / CSS transitions)
- 🗺️ Integrate weather maps (e.g., precipitation, temperature overlays)
- 🧪 Add tests and accessibility improvements (ARIA labels, keyboard navigation)

---

## Contributing
Contributions are welcome! If you'd like to contribute:
1. Fork the repository
2. Create a new branch (feature or fix): `git checkout -b feat/your-feature`
3. Make changes and commit: `git commit -m "Add your feature"`
4. Push to your fork and open a pull request

Please include clear descriptions for changes and screenshots if UI is affected.

---

## Author
Pratham Sharma  
B.Tech CSE Student | Full-Stack Developer  
GitHub: [Pratham-Sharma20](https://github.com/Pratham-Sharma20)

---

## Acknowledgements
- Open-Meteo — free weather and geocoding APIs (no API key required)
- Inspirations and UI ideas from public weather dashboards and design resources
