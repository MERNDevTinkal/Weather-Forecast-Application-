# Weather Forecast Application 🌦️

Welcome to the **Weather Forecast Application**! This web application allows users to view current weather conditions and an extended forecast for different locations. It is built using **JavaScript**, **HTML**, **CSS**, and **Tailwind CSS** for styling, with real-time weather data fetched from an external **Weather API**.

You can view the live version of this project [here](http://merndevtinkal.com/).

## Features 🚀

1. **Weather API Integration**: Fetches real-time weather data using the [OpenWeatherMap API](https://openweathermap.org/) (or any chosen API).
2. **Location-based Forecasts**: Allows users to search for weather forecasts by:
   - **City name**
   - **Current location**
3. **Extended Forecast**: Displays a 5-day forecast with key details such as temperature, humidity, wind speed, and weather icons.
4. **Recently Searched Cities**: Keeps track of recently searched cities, with a dropdown menu for quick access.
5. **Responsive Design**: Optimized for multiple screen sizes (Desktop, iPad Mini, iPhone SE).
6. **Error Handling**: Provides user-friendly messages for invalid inputs or API errors.

## Project Structure 🗂️

The project follows a simple file structure:

```plaintext
├── index.html
├── css
│   └── output.css (Tailwind CSS)
├── js
│   └── app.js (Main JavaScript logic)
├── README.md (This file)
└── .gitignore
```

## How to Use 📋

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MERNDevTinkal/weather-forecast-app.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd weather-forecast-app
   ```
3. **Install dependencies** (if applicable):
   ```bash
   npm install
   ```
4. **Run the project**:
   Open the `index.html` file in your browser.

## Deployment on GitHub Pages 🌐

This project is deployed via **GitHub Pages**. Visit the live site [here](http://merndevtinkal.com/).

To redeploy the project:
1. Commit and push your changes to the main branch.
2. Your changes will automatically reflect on GitHub Pages.

## API Integration 🔗

- We use the **OpenWeatherMap API** to fetch the weather data. Sign up [here](https://openweathermap.org/) to get your own API key.
- Replace the placeholder API key in the `app.js` file with your own:
   ```javascript
   const apiKey = 'YOUR_API_KEY';
   ```

## Screenshots 📸

### Home Page
![Home Page Screenshot](path/to/screenshot.png)

### Extended Forecast
![Extended Forecast Screenshot](path/to/screenshot.png)

## Technologies Used 💻

- **JavaScript**
- **HTML5**
- **CSS3** (with **Tailwind CSS** for responsive styling)
- **OpenWeatherMap API**

## Future Enhancements 🌱

- Add **hourly weather forecasts**.
- Implement **dark mode** for better accessibility.
- Provide support for multiple languages.

## Contributing 🤝

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/MERNDevTinkal/weather-forecast-app/issues) if you want to contribute.

## License 📝

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.
