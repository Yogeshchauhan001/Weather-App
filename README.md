This code creates a Weather App with International Clocks, allowing users to search for a city and view its current weather alongside live clocks for London, Tokyo, and Sydney.

Features:
Weather Search: A search bar lets users type a city name to fetch weather data via the OpenWeatherMap API. The app displays city details, temperature, weather description, and min/max temperatures.
Live Clocks: Real-time clocks show current times for London, Tokyo, and Sydney, updating every second based on their respective time zones.
Modern UI Design: Includes a gradient background, card-style layout, rounded corners, and responsive fonts for a clean, professional look.
How It Works:
The user searches for a city, and the app dynamically updates the weather data, including temperature and conditions.
Clocks for global cities are calculated using toLocaleString and update with setInterval.
Suggestions:
Add error messages for invalid cities or failed API requests.
Improve layout for mobile responsiveness using CSS media queries.
Include weather icons or animations for better user experience.
Expand international clocks to include more cities.
