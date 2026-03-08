# Weather Dashboard (Next.js)

A modern **Weather Dashboard** built with **Next.js and TypeScript** that displays real-time weather information including temperature, forecasts, air pollution, and UV index.

The application integrates multiple weather APIs and demonstrates modern web development practices such as API integration, server actions, and caching.

---

# Features

* Current weather information
* Hourly forecast
* Daily temperature forecast
* Air pollution data
* UV index monitoring
* Multiple saved cities
* Fast server-side data fetching

---

# Tech Stack

Frontend

* Next.js
* React
* TypeScript
* Tailwind CSS

APIs

* OpenWeather API
* Open-Meteo API

Tools

* Node.js
* Git
* npm

---

# Application Architecture

```
User Browser
      │
      ▼
Next.js Application
(Server Components + API Functions)
      │
      ▼
Weather API Layer
(OpenWeather + Open-Meteo)
      │
      ▼
Weather Data Response
(JSON)
      │
      ▼
UI Components Render Data
```

---

# Screenshots

## Weather Dashboard

Add your screenshot here:

```
/screenshots/dashboard.png
```

Example display:

* Current temperature
* Weather conditions
* Hourly forecast
* UV index
* Air pollution

## Forecast View

```
/screenshots/forecast.png
```

Shows hourly and daily weather predictions.

---

# Installation

Clone the repository

```bash
git clone https://github.com/sagarsaini12/weather-dashboard.git
```

Move into project directory

```bash
cd weather-dashboard
```

Install dependencies

```bash
npm install
```

Create environment file

Create `.env.local` in the root directory and add:

```
OPENWEATHER_API_KEY=your_api_key_here
```

Start development server

```bash
npm run dev
```

Open in browser

```
http://localhost:3000
```

---

# Project Structure

```
actions/
  weather.ts        API requests

app/
  page.tsx          Main dashboard page

components/
  WeatherCard
  ForecastList
  PollutionInfo

hooks/
  custom React hooks

types/
  TypeScript interfaces
```

---

# How the Application Works

1. The user opens the weather dashboard.
2. The application sends requests to weather APIs.
3. API responses return weather data in JSON format.
4. Server actions process the data.
5. UI components display the weather information.

---

# Future Improvements

* Search weather by city name
* Location-based weather detection
* Weather charts using graphs
* Dark mode
* Mobile responsive improvements

---

# License

MIT License
