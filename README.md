# 🌤️ Weather App

A sleek, glassmorphic weather application that delivers real-time weather conditions and a 5-day forecast for any city in the world — built with pure HTML, CSS, and JavaScript.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![OpenWeatherMap API](https://img.shields.io/badge/API-OpenWeatherMap-orange?style=flat)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## ✨ Features

- 🔍 **City Search** — Search weather conditions for any city, worldwide
- 🌡️ **Live Weather Data** — Current temperature, condition, humidity, and wind speed
- 📅 **5-Day Forecast** — Scrollable daily forecast with weather icons
- 🎨 **Dynamic Weather Icons** — Icons update automatically based on live conditions (clear, clouds, rain, drizzle, thunderstorm, snow, atmosphere)
- 🧊 **Glassmorphism UI** — Frosted-glass card design with a blurred background
- ⚠️ **Graceful Empty & Error States** — Friendly prompts for the initial screen and invalid city searches
- 📱 **Compact, Responsive Layout** — Lightweight single-card interface

## 🖼️ Preview

| Search State | Weather Info |
|---|---|
| Prompt to search a city | Current conditions + forecast |

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (Glassmorphism, Flexbox) |
| Logic | Vanilla JavaScript (ES6+, async/await) |
| Data | [OpenWeatherMap API](https://openweathermap.org/api) |
| Icons | Google Material Symbols |
| Font | [Poppins](https://fonts.google.com/specimen/Poppins) (Google Fonts) |

## 📁 Project Structure

```
weather-app/
├── assets/
│   ├── bg.jpg            # Background image
│   ├── weather/          # Weather condition icons (clear, rain, snow, etc.)
│   └── message/          # Empty-state and not-found illustrations
├── index.html            # App markup
├── style.css             # Styling and layout
└── script.js             # Weather fetching and rendering logic
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- A free API key from [OpenWeatherMap](https://home.openweathermap.org/api_keys)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Kishore2005-Tech/weather-app.git
   cd weather-app
   ```

2. **Add your API key**

   Open `script.js` and paste your OpenWeatherMap API key:
   ```javascript
   const apiKey = 'YOUR_API_KEY_HERE'
   ```

3. **Run the app**

   Simply open `index.html` in your browser, or serve it locally:
   ```bash
   npx serve .
   ```

> **Note:** New OpenWeatherMap API keys can take a few minutes to a couple of hours to activate.

## 🎯 How It Works

1. Enter a city name and press **Enter** or click the search icon.
2. The app calls the OpenWeatherMap `weather` endpoint for current conditions and the `forecast` endpoint for the 5-day outlook.
3. Weather condition codes are mapped to matching SVG icons (thunderstorm, drizzle, rain, snow, atmosphere, clear, clouds).
4. If the city isn't found, a **"Not Found"** state is shown instead of the weather card.

## 🗺️ Roadmap

- [ ] Geolocation-based auto-detection of the user's current city
- [ ] Toggle between °C and °F
- [ ] Hourly forecast view
- [ ] Recent search history
- [ ] Light/dark theme toggle

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

## 👤 Author

**Kishore**
- GitHub: [@Kishore2005-Tech](https://github.com/Kishore2005-Tech)

---

<p align="center">⭐ If you found this project useful, consider giving it a star!</p>
