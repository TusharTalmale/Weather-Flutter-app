# 🌦️ Flutter Weather App

A beautiful Flutter weather application that displays current weather, hourly forecasts, and additional weather information using the OpenWeatherMap API. You can search by city (with optional country code) or use your current GPS location.

## 🎬 Demo Video

[![Watch the video](https://img.youtube.com/vi/umXKlLSedMY/0.jpg)](https://youtu.be/umXKlLSedMY)

## 🚀 Features

- 🔍 Search weather by city name (with optional country code, e.g., `Mumbai,Ind`)
- 🌡️ Temperature in Celsius (converted from Kelvin)
- 🕐 Hourly weather forecast
- 💧 Humidity, wind speed, and pressure info
- 🎨 Clean and modern UI with Material Design

## 🔧 Tech Stack

- **Flutter**
- **Dart**
- **OpenWeatherMap API**
- **HTTP package**

## 📦 Dependencies

Add these to your `pubspec.yaml`:

```yaml
dependencies:
  flutter:
    sdk: flutter
  http: ^0.13.6
  intl: ^0.18.1
