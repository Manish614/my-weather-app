# 🌤️ Weather App

A simple and responsive weather application built using **HTML**, **CSS**, and **JavaScript**. This app allows users to search and view real-time weather updates for any city around the world.  

It fetches data from the **OpenWeatherMap API** and displays details like **temperature**, **weather condition**, **humidity**, and **wind speed**.

---

## 🚀 Features

- 🔍 Search weather info by city name
- 🌦️ Displays:
  - Temperature in °C
  - Weather condition (e.g., clear sky, rain, overcast)
  - Humidity (%)
  - Wind speed (Km/hr)
- ❌ Shows an error message if the city is not found
- 📱 Responsive and modern UI with animated transitions

---

## Demo & Images

![Search Location](./demo1.jpeg)  
*Enter Location and Search*

![Know the Weather Conditions](./demo2.jpeg)  
*Know temperature, weather condition, humidity, and wind speed*

---

## 📦 Project Structure

```
my-weather-app/
├── index.html          # Main HTML file
├── style.css           # CSS styling
├── script.js           # JavaScript logic
└── assets/             # Weather icons & images
```

---

## ⚙️ How It Works

1. User enters a city name
2. App sends a request to OpenWeatherMap API
3. If the location exists — shows weather details
4. If not — displays a “location not found” message

---

## 🔧 Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- OpenWeatherMap API

---

## ✅ How to Run Locally

```bash
# Clone the repository
git clone https://github.com/Manish614/my-weather-app.git

# Open the HTML file in your browser
cd my-weather-app
open index.html   # or just double-click the file
```

---

## 📌 Notes

- The app uses metric units (°C and Km/hr)
- You must have an active internet connection to fetch live data
- API Key is hardcoded for learning/demo purposes — don’t use this method in production

---

## 🙌 Acknowledgements

- [OpenWeatherMap](https://openweathermap.org) — for providing free weather data
- [Font Awesome](https://fontawesome.com) — for icons

---

## 💻 Live Demo

👉 Live site: [View on Vercel](https://my-weather-app-mauve-seven.vercel.app/)

---

## 📜 License

This project is open-source and free to use for learning and personal practice.
