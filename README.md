# ⛅ Weather CLI App

A simple yet powerful **command-line weather application** that fetches real-time weather data for any city in the world 🌍.

![Weather CLI Demo](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExeXhrYjR5dXgxOWpqMzVpZXo2N3hsbjV3ZTZmdnBvaG5uZHpsMnM3eSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/5bnpFBKcGArJrwHwaX/giphy.gif)

---

## ✨ Features

- 🌐 **Real-time Weather** – Get current weather for any city worldwide  
- 📋 **Detailed Reports** – Includes temperature, "feels like", humidity, and conditions  
- ❌ **Error Handling** – Retries up to 3 times for failed requests  
- 📝 **History Logging** – Saves queries to `weather_history.txt` automatically  
- ⚡ **Lightweight** – No external JSON libraries required (manual parsing)

---

## ⚙️ Prerequisites

- Java JDK **11 or higher**
- Internet connection (required to fetch data from API)

---

## 🚀 Installation

```bash
git clone https://github.com/yourusername/weather-cli.git
cd weather-cli
javac *.java
```

---

## 📦 Usage

```bash
java Main
```

**Then follow the prompts:**

1. Enter a city name (e.g., `London`)
2. Enter a country code (e.g., `GB` for United Kingdom)

---

## ✅ Example Output

```plaintext
=== Weather CLI App ===
-------------------------------------------------------------
Enter city (e.g. London): Tokyo
Enter country code (e.g. GB): JP

--- Weather Report ---
City        : Tokyo
Temperature : 22.5°C
Feels Like  : 24.3°C
Humidity    : 65%
Condition   : cloudy

📁 Weather history saved to weather_history.txt
```

## 🔑 API Key Note

This app uses a built-in API key for [OpenWeatherMap](https://openweathermap.org/api). For long-term or production usage:

1. **Get your free API key** from OpenWeatherMap  
2. **Store it securely** (e.g., as an environment variable)  
3. **Update** `WeatherService.java` to use your custom key

---

## 🤝 Contributing

Pull requests are welcome!  
For major changes, please open an issue first to discuss your ideas.

---

## 📄 License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).

---

> 🌤️ Check the weather with style — straight from your terminal! ⛈️
