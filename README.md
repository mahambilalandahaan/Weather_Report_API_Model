# ⛈ WEATHER REPORT API PROJECT

### 🧠 Overview  
The **Weather Report API Project** fetches real-time weather details of any city using the **OpenWeatherMap API** and automatically generates a formatted **Markdown report**.  

This project demonstrates:  
- API integration using Python’s `requests` library.  
- Secure API key handling with `google.colab.userdata`.  
- JSON parsing and data extraction.  
- Local time and sunrise/sunset calculations.  
- Beautiful Markdown output with emojis and formatting.  

---

### ⚙️ Features  
✅ Fetches **live weather data** for any city in the world.  
✅ Displays temperature in both °C and °F.  
✅ Converts **UTC time** to **local city time**.  
✅ Includes **humidity, wind speed, sunrise & sunset** info.  
✅ Saves each report into `Weather_Report.md` for future reference.  
✅ User-friendly menu for multiple queries in one run.  

---

### 🧩 Tech Stack  

| Tool / Library | Purpose |
|-----------------|----------|
| `requests` | For sending API requests |
| `datetime` | For time and timezone handling |
| `google.colab.userdata` | To securely store API key |
| `OpenWeatherMap API` | Weather data provider |
| `Markdown` | Report formatting and saving |

---

### 🧰 Setup Instructions  
1. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api).  
2. Store your key securely in Google Colab:  
   ```python
   from google.colab import userdata  
   userdata.set('OR_API_KEY', 'your_api_key_here')
Copy and run the main script in a Colab cell.
Enter any city name and view the weather report.
🌤️ Weather Report for Lahore, PK WN  

**EXAMPLE MARKDOWN TABLE**📰

| **Field** | **Value** |
|:-----------------|:-----------------------------|
| 🌆 City | Lahore |
| 🌍 Country | PK |
| 🌡 Temperature | 27.45°C / 81.41°F |
| 🌡 Feels Like | 26.89°C / 80.40°F |
| ☁️ Weather | clear sky |
| 💧 Humidity | 44% |
| 🌬 Wind Speed | 2.57 m/s (9.25 km/h) |
| 🌅 Sunrise | 2025-10-18 06:13:42 |
| 🌇 Sunset | 2025-10-18 17:39:19 |
| 🕕 Local Time | 2025-10-18 22:15:37 |

🕝 Report generated at 2025-10-18 22:15:37

**OUTPUT FILE**📁

All reports are saved automatically to:  
Weather_Report.md  

Each new weather request appends a new section in this file.

🏆**Conclusion**

This project is a great demonstration of real-time API handling, data formatting, and automation with Python.  
It can be expanded to include:  

- Multi-day forecasts  
- Data visualization (temperature trends)  
- Separate files per city  


👩‍💻 **Developed by:** Madiha Atif  
📆 **Project Date:** October 2025
