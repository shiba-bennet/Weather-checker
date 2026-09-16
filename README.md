# 🌤️ Weather Intelligence App

A responsive web application that fetches real-time weather data and 7-day forecasts for cities worldwide using the Open-Meteo public API. Built with React, Vite, and Tailwind CSS, and deployed on Cloudflare Pages.

---

## 🚀 Live Demo

- **Live Cloudflare Pages URL:** `https://weather-checker.pages.dev`
- **GitHub Repository:** `https://github.com/shiba-bennet/weather-checker`

---

## ✨ Features

- **City Search:** Real-time city name lookup via Open-Meteo Geocoding API.
- **Current Conditions:** Displays temperature (°C), weather icons, wind speed, and precipitation.
- **7-Day Forecast:** Daily forecast cards highlighting max/min temperatures.
- **Interactive Visualizations:** Recharts line chart plotting 7-day temperature trends.
- **Smart Recommendations:** Automated planning insights (e.g., rain alerts, outdoor advice).
- **Error Handling:** Graceful error messages for invalid or un-found city queries.

---

## 🛠️ Tech Stack & APIs

- **Frontend:** React, Vite, Tailwind CSS, Lucide Icons, Recharts
- **APIs Used (No API Key Required):**
  - **Geocoding API:** `https://geocoding-api.open-meteo.com/v1/search`
  - **Forecast API:** `https://api.open-meteo.com/v1/forecast`
- **Deployment Platform:** Cloudflare Pages

---

## ⚙️ Deployment & Build Configuration

This application was generated using Google AI Studio App Build, pushed directly to GitHub, and deployed on Cloudflare Pages.

- **Framework Preset:** Vite
- **Build Command:** `npm run build`
- **Build Output Directory:** `dist`
- **Node Version:** 18+

---

## 🏃 Local Setup & Development

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/shiba-bennet/weather-checker.git](https://github.com/shiba-bennet/weather-checker.git)
   cd weather-checker
