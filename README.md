# 🌤️ Weather Application with PyQt5

A simple and elegant weather application built with Python and PyQt5 that provides real-time weather information with a beautiful graphical user interface.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![PyQt5](https://img.shields.io/badge/PyQt5-GUI-green)
![Weather API](https://img.shields.io/badge/Weather-API-orange)

## 🎯 Overview

This desktop application allows users to check current weather conditions for any city worldwide. Built with PyQt5, it features a clean, intuitive interface that displays temperature, humidity, wind speed, and other weather metrics.

## ✨ Features

- 🌍 **Global Coverage** - Check weather for any city worldwide
- 🌡️ **Real-time Data** - Current weather conditions
- 💨 **Detailed Information** - Temperature, humidity, wind speed, pressure
- 🎨 **Beautiful GUI** - Clean PyQt5 interface
- 🔍 **City Search** - Easy location lookup
- 🌤️ **Weather Icons** - Visual weather condition indicators
- ⚡ **Fast & Responsive** - Quick data fetching

## 🛠️ Technologies Used

- **Python** - Core programming language
- **PyQt5** - GUI framework
- **OpenWeatherMap API** - Weather data provider
- **Requests** - HTTP library for API calls
- **JSON** - Data parsing

## 🚀 Installation

### Prerequisites
```bash
pip install PyQt5 requests
```

### API Setup
1. Get free API key from [OpenWeatherMap](https://openweathermap.org/api)
2. Add your API key to the configuration file

### Running the Application
```bash
# Clone the repository
git clone https://github.com/PURON98/simple-weather-software-by-pyqt5.git
cd simple-weather-software-by-pyqt5

# Run the application
python weather_app.py
```

## 📁 Project Structure

```
simple-weather-software-by-pyqt5/
├── weather_app.py           # Main application
├── gui/                     # GUI components
│   ├── main_window.py      # Main window design
│   └── weather_widget.py   # Weather display widget
├── api/                     # API handling
│   └── weather_api.py      # OpenWeatherMap integration
├── resources/              # Icons and images
│   └── icons/              # Weather icons
├── config.py               # Configuration file
└── README.md              # Documentation
```

## 💻 Usage

1. **Launch the Application**
   ```bash
   python weather_app.py
   ```

2. **Search for a City**
   - Enter city name in search box
   - Press Enter or click Search button

3. **View Weather Data**
   - Current temperature
   - Weather description
   - Humidity percentage
   - Wind speed
   - Atmospheric pressure
   - Feels like temperature

## 🌤️ Weather Information Displayed

- **Temperature** - Current temperature in Celsius/Fahrenheit
- **Description** - Weather condition (Clear, Cloudy, Rainy, etc.)
- **Humidity** - Moisture percentage in air
- **Wind Speed** - Current wind velocity
- **Pressure** - Atmospheric pressure
- **Visibility** - Visual range
- **Sunrise/Sunset** - Day/night timings

## 🎨 GUI Features

### Main Window
- Clean and modern design
- Search bar for city input
- Weather display panel
- Temperature unit toggle (°C/°F)

### Weather Display
- Large temperature display
- Weather icon representation
- Detailed metrics grid
- Color-coded information

### Responsive Design
- Adjusts to different screen sizes
- Smooth animations
- Error handling notifications

## 🔧 Configuration

```python
# config.py
API_KEY = "your_openweathermap_api_key"
DEFAULT_CITY = "London"
UNITS = "metric"  # or "imperial"
LANGUAGE = "en"
UPDATE_INTERVAL = 300  # seconds
```

## 📊 API Integration

### OpenWeatherMap API
- Current weather data
- 5-day forecast (future enhancement)
- Weather alerts
- Historical data

### Request Example
```python
import requests

url = f"http://api.openweathermap.org/data/2.5/weather"
params = {
    "q": city_name,
    "appid": API_KEY,
    "units": "metric"
}
response = requests.get(url, params=params)
```

## 🎯 Applications

- 📱 **Personal Use** - Daily weather checks
- 🚗 **Travel Planning** - Weather-based itinerary
- 🌾 **Agriculture** - Farming decisions
- 📸 **Photography** - Weather for outdoor shoots
- 🎓 **Education** - Learning weather patterns

## 🎓 Key Concepts

- **GUI Development** - PyQt5 framework
- **API Integration** - RESTful API consumption
- **JSON Parsing** - Data extraction
- **Event Handling** - User interactions
- **Error Handling** - API failures and invalid inputs

## 🎯 Future Enhancements

- [ ] 5-day weather forecast
- [ ] Hourly predictions
- [ ] Weather maps
- [ ] Multiple city tracking
- [ ] Weather alerts/notifications
- [ ] Historical weather data
- [ ] Weather graphs and charts
- [ ] Location auto-detection
- [ ] Dark mode theme
- [ ] Minimalist tray icon

## 🌟 Features in Development

### Advanced Features
- Weather radar integration
- Air quality index
- UV index information
- Pollen count
- Weather-based recommendations

### UI Improvements
- Animated weather backgrounds
- Custom themes
- Widget customization
- Multi-language support

## 🐛 Troubleshooting

**API Key Error**
```
Solution: Ensure valid API key in config.py
```

**City Not Found**
```
Solution: Check spelling, try major city names
```

**Connection Error**
```
Solution: Check internet connection
```

## 🤝 Contributing

Contributions welcome! Areas for improvement:
- Additional weather features
- UI enhancements
- New API integrations
- Performance optimizations

## 📚 Resources

- [OpenWeatherMap API Documentation](https://openweathermap.org/api)
- [PyQt5 Documentation](https://www.riverbankcomputing.com/static/Docs/PyQt5/)
- [Python Requests Library](https://docs.python-requests.org/)

## 📝 License

This project is open source and available for educational purposes.

## 👨‍💻 Author

**Tabiul Mursalin Puron**
- GitHub: [@PURON98](https://github.com/PURON98)

## 🙏 Acknowledgments

- OpenWeatherMap for free API
- PyQt5 community
- Weather icons contributors

---

⭐ If this weather app helps you plan your day, please star it!

<p align="center">
  🌤️ Stay informed about the weather! 🌤️
</p>