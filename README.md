# API-based-Weather-App

![Screenshot 2024-05-23 131435](https://github.com/divya-gadekar28/API-based-Weather-App/assets/116143709/9ed3407c-820b-44e7-828b-603301e966b8)

![Screenshot 2024-05-23 131419](https://github.com/divya-gadekar28/API-based-Weather-App/assets/116143709/a956e23a-ee4f-43c2-91b2-3d3923e8c09a)



## Overview
This Weather App is a simple and intuitive web application that provides real-time weather forecasts for any location around the world. The app is built using HTML, CSS, and JavaScript, and it leverages the OpenWeather API to fetch live weather data.

## Features
- **Real-time Weather Data**: Get current weather information including temperature, weather conditions, humidity, and wind speed.
- **Location Search**: Easily search for weather data by entering the name of any city or location.
- **Dynamic Icons and Images**: Display dynamic icons and images that correspond to the current weather conditions.
- **Responsive Design**: The app is fully responsive and works seamlessly on both desktop and mobile devices.
- **Error Handling**: Informative messages for invalid location searches.

## Technologies Used
- **HTML**: Provides the structure of the app.
- **CSS**: Used for styling the app, making it visually appealing and responsive.
- **JavaScript**: Implements the app's functionality, including fetching data from the API and updating the UI dynamically.
- **OpenWeather API**: Used to retrieve live weather data.

## How It Works
1. **User Input**: The user enters a location (city name) in the search box.
2. **Fetch Weather Data**: The app makes a request to the OpenWeather API using the entered location.
3. **Display Data**: The fetched weather data is then displayed in the app, including temperature, weather description, humidity, and wind speed.
4. **Error Handling**: If the location is not found, an error message is displayed to the user.

## Setup and Installation
To set up and run the app locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```

2. Open `index.html` in your preferred web browser.

## Configuration
To use the OpenWeather API, you need to sign up for an API key:-

1. Go to the [OpenWeather API](https://openweathermap.org/api) website.
2. Sign up for a free account and generate an API key.
3. Replace the placeholder `YOUR_API_KEY` in the `script.js` file with your actual API key.

```javascript
const apiKey = 'YOUR_API_KEY';
```

## File Structure
```plaintext
weather-app/
├── assets/
│   ├── 404.png
│   └── cloud.png
├── index.html
├── style.css
└── script.js
```

- **index.html**: The main HTML file that contains the structure of the app.
- **style.css**: The CSS file for styling the app.
- **script.js**: The JavaScript file that contains the logic for fetching and displaying weather data.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request or open an issue.

## Acknowledgements
- Thanks to [OpenWeather](https://openweathermap.org/) for providing the weather data API.

---

