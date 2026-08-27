# 🌤️ Weather App

A simple desktop weather application built with **Python and PyQt5** that allows users to enter a city name and retrieve its current weather information using the **OpenWeatherMap API**.

The application displays the current temperature, weather condition emoji, and a short description of the weather.

## 📌 Features

* 🌍 Search weather by city name
* 🌡️ Display current temperature in Celsius
* 🌤️ Display weather condition using emojis
* 📝 Display a description of the current weather
* ⚠️ Handles different HTTP/API errors
* 🌐 Handles connection, timeout, and request errors
* 🖥️ Simple graphical user interface built with PyQt5
* 🎨 Custom styling using Qt Style Sheets

## 🛠️ Technologies Used

* **Python**
* **PyQt5** — GUI development
* **Requests** — HTTP requests to the weather API
* **OpenWeatherMap API** — Weather data

## 📂 Project Structure

```text
weather-app-python/
│
├── main.py
├── README.md
└── ...
```

## ⚙️ Requirements

Make sure you have Python installed on your system.

Install the required Python packages:

```bash
pip install PyQt5 requests
```

## 🔑 API Key

This application uses the **OpenWeatherMap API** to retrieve weather information.

You need an OpenWeatherMap API key to run the application.

Create an account on OpenWeatherMap and obtain an API key from your account.

Then configure the API key in the Python program before running the application.

> **Security note:** Do not commit your API key directly to a public GitHub repository. For a production-ready project, store the key in an environment variable or a `.env` file.

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/chinmay21/weather-app-python.git
```

Navigate into the project directory:

```bash
cd weather-app-python
```

Install the dependencies:

```bash
pip install PyQt5 requests
```

Run the application:

```bash
python main.py
```

## 🖥️ How to Use

1. Launch the application.
2. Enter the name of a city.
3. Click **Get weather**.
4. The application retrieves the city's current weather information.
5. The temperature, weather emoji, and description are displayed in the application.

For example:

```text
Enter city name:
[ New Delhi ]

[ Get weather ]

        32°C
          ☀️
       Clear sky
```

## 🚨 Error Handling

The application handles several possible errors, including:

* Bad requests
* Invalid API keys
* Forbidden requests
* City not found
* Server errors
* Bad gateway responses
* Service unavailable errors
* Gateway timeouts
* Internet connection errors
* Request timeouts
* Too many redirects
* Other request-related errors

This allows the application to provide a meaningful message instead of crashing when something goes wrong.

## 🧠 What I Practiced

This project helped reinforce several Python concepts:

* Object-oriented programming with classes
* Functions and methods
* Static methods
* Exception handling
* HTTP requests
* Working with REST APIs
* JSON data parsing
* GUI development with PyQt5
* Qt layouts and widgets
* Qt Style Sheets
* Conditional logic
* API response handling

## 🔮 Possible Improvements

Some improvements that could be added in the future:

* 🌡️ Add humidity and wind speed
* 📅 Add a multi-day weather forecast
* 🌍 Display the country and coordinates
* 🔐 Move the API key to environment variables
* 🌙 Add dark/light mode
* 📊 Add weather statistics
* 🔄 Add a refresh button
* 🎨 Improve the overall UI
* ⏳ Add a loading indicator
* 📱 Make the interface more responsive

## 📄 License

This project is available for learning and personal use.