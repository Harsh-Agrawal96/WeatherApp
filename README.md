# Weather App

A simple weather application that allows users to get the current weather details for a specific location and city.

---

## Features

- 🌤️ **Search for weather** by city name.
- 🌡️ **Display current weather conditions** (temperature, humidity, etc.).
- 📱 **Responsive design** for all devices.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **API**: OpenWeatherMap API

---

## API Endpoints

### **Public Endpoints**
| Method    | Endpoint                      |  Description                                            |
|-----------|-------------------------------|---------------------------------------------------------|
| GET       | `/`                           |  Access the weather app                                 |
| GET       | `/weather?address=city_name`  |  Retrieve the weather details for the particular city   |

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Harsh-Agrawal96/WeatherApp.git
   cd WeatherApp
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and add your API key for the OpenWeatherMap API:
   ```env
   API_KEY=your_openweathermap_api_key
   PORT=3000
   ```

4. **Run the Application**:
   ```bash
   npm start
   ```

5. **Access the App**:
   Open your browser and navigate to `http://localhost:3000`.

---

## Usage

1. Enter the city name in the search bar.
2. View the current weather details and forecast.

## Project Structure

```
weather-app/
├── public/
│   ├── css/
│   └── js/
├── templates/
│   ├── partials/
│   └── views/
├── utils/
├── .env
├── .gitignore
├── package.json
├── index.js
└── README.md
```

## Acknowledgments

- [OpenWeatherMap API](https://openweathermap.org/api) for weather data.
- Tutorials and resources from the web.
