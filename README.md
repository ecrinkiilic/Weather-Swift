# Weather Swift ☀️🌧️

A simple iOS weather application built with **Swift**. The app fetches real-time weather data from an API and presents current weather information through a clean and user-friendly interface.

## Features

- Get real-time weather information
- Search weather by city name
- Display temperature, humidity, and weather conditions
- JSON parsing with `Decodable`
- Responsive and intuitive UI
- Error handling for network requests

## Technologies Used

- Swift
- UIKit
- URLSession
- JSONDecoder
- REST API Integration
- Core Location (if used)

## Screenshot



<p align="center">
  <img src="https://github.com/user-attachments/assets/ab5edb40-bb61-469c-a074-1e3c4c8b2b1c" width="300" alt="Weather App Screenshot">
    <img src="https://github.com/user-attachments/assets/157473d9-d3d0-46e7-9ff3-b5f419e680ba" width="300" alt="Weather App Screenshot">
  <img src="https://github.com/user-attachments/assets/d1853bda-259a-4833-957f-4ec92effaaae" width="300" alt="Weather App Screenshot">

</p>

## Project Structure

```text
Weather-Swift
├── Model
├── Service
├── View
├── Controller
└── Assets.xcassets
```

## Installation

Clone the repository:

```bash
git clone https://github.com/ecrinkiilic/Weather-Swift.git
```

Open the project in Xcode and run it on a simulator or a physical device.

## How It Works

- The app sends a request to a weather API using `URLSession`.
- The JSON response is decoded into Swift models using `Decodable`.
- Weather information is displayed dynamically on the user interface.
- Users can search for different cities to view their current weather conditions.

## Learning Outcomes

This project was developed to practice:

- API integration in Swift
- Working with JSON data
- Asynchronous network operations
- Building user interfaces with UIKit
- Error handling and data modeling

## Future Improvements

- 7-day weather forecast
- Dark mode support
- Dynamic weather animations
- Favorite cities feature
- Localization support

## Author

**Ecrin Kılıç**

GitHub: https://github.com/ecrinkiilic
