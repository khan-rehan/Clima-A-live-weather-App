# Clima - Live Weather App

![Author - Rehan Khan](https://img.shields.io/badge/Author-Rehan%20Khan-blue)

A Flutter weather application that fetches real-time weather data for any city worldwide. Uses GPS location to get current weather or allows manual city search.

## Features

- Get weather for your current location via GPS
- Search weather by city name
- Displays temperature, weather condition, and description
- Weather condition icons and messages
- Dark-themed UI

## Tech Stack

- **Framework:** Flutter
- **Language:** Dart
- **API:** [OpenWeatherMap](https://openweathermap.org/current)
- **Location:** [Flutter Geolocator Plugin](https://pub.dev/packages/geolocator)
- **HTTP:** Dart HTTP package

## Project Structure

```
lib/
├── main.dart
├── screens/
│   ├── loading_screen.dart      # Initial screen, fetches location
│   ├── location_screen.dart     # Displays weather data
│   └── city_screen.dart         # City search input
├── services/
│   ├── location.dart            # GPS location service
│   ├── networking.dart          # API networking
│   └── weather.dart             # Weather data handler
└── utilities/
    └── constants.dart           # App styling constants
```

## Setup

**Prerequisites:** [Flutter SDK](https://flutter.dev/docs/get-started/install), an [OpenWeatherMap API key](https://openweathermap.org/appid)

```sh
git clone https://github.com/khan-rehan/Clima-A-live-weather-App.git
cd Clima-A-live-weather-App
flutter run
```

## Demo

![Clima Demo](clima.gif)

## Screenshot

<img width="217" alt="Clima" src="https://user-images.githubusercontent.com/42263217/79532535-0aebe100-8093-11ea-93fe-49b032be61dd.png">
