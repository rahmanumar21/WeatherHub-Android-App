# WeatherHub

WeatherHub is a simple weather forecast application that provides weather information for cities worldwide.

## Features

- Bcrypt algorithm for User Account Security.
- Local user registration and login system connected to Local Database (SQLite).
- Prevents Duplicate Registrations: The application ensures that if a user attempts to register with an email that is already registered, it will be rejected, and a message 
  indicating that the email is already registered will be displayed.
- Persistent login session.
- Dashboard displaying user profile and weather forecast data.
- Integration with [OpenWeatherMap API](https://openweathermap.org/) for weather forecast data.
- Current weather information for any city.
- Automatic location detection to provide local weather updates.
- Clean and intuitive user interface.
- Logout functionality.

### Prerequisites

- Android Studio
- Android SDK
- API key from OpenWeatherMap (https://openweathermap.org/)

### Installation

1. Clone the repository.
   
2. Open the project in Android Studio.

4. Replace `YOUR_API_KEY` in the `api_config.properties` with your OpenWeatherMap API key.

5. Build and run the app.

### Usage

- Enter the city name and click the "Search" button for the latest weather information.
- Allow location permission to detect your current location weather automatically.

### Screenshots

- Splash Screen
  
![Splash Screen](screenshots/Splash%20Screen.jpg)

- Login
  
![Splash Screen](screenshots/Login.jpg)

- Registration
  
![Splash Screen](screenshots/Registration.jpg)

- Dashboard
  
![Splash Screen](screenshots/Dashboard.jpg)




