# Weather App

A simple, responsive weather application that allows users to check current weather conditions for any city. Built with HTML, CSS, and JavaScript using the OpenWeatherMap API.

![Weather App Demo]![image](https://github.com/user-attachments/assets/2361afa8-63a9-4bf6-9c14-f132ceb7481f)


## Features

- Real-time weather data fetching
- Current temperature display
- Humidity information
- Wind speed information
- Weather condition icons
- Responsive design for all devices
- Error handling for invalid city names

## Technologies Used

- HTML5
- CSS3
- JavaScript (Async/Await)
- OpenWeatherMap API

## Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/chandrakant1212/weather-app
```

2. Get an API key:
   - Sign up at [OpenWeatherMap](https://openweathermap.org/)
   - Navigate to API keys section
   - Copy your API key

3. Create a script.js file and replace the API key:
```javascript
const apiKey = a027f4a2e05d9a1d6804d9fb59b5550e;
```

4. Make sure you have all required images in the `images` folder:
   - search.png
   - clear.png
   - rain.png
   - clouds.png
   - drizzle.png
   - mist.png
   - humidity.png
   - wind.png

5. Open `index.html` in your web browser

## Project Structure

```
weather-app/
│
├── index.html
├── style.css
├── script.js
├── README.md
│
└── images/
    ├── search.png
    ├── clear.png
    ├── rain.png
    ├── clouds.png
    ├── drizzle.png
    ├── mist.png
    ├── humidity.png
    └── wind.png
```

## Usage

1. Enter a city name in the search box
2. Click the search button or press Enter
3. View the current weather conditions for the specified city
4. If the city name is invalid, an error message will be displayed

## API Reference

The app uses the OpenWeatherMap API to fetch weather data:
```javascript
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_key}&units=metric
```

## Responsive Design

The app is responsive and works on:
- Mobile devices (320px and up)
- Tablets (768px and up)
- Desktop screens (1024px and up)

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Weather data provided by OpenWeatherMap
- Font from Google Fonts (Poppins)
