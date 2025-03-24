Below is an example of source code for a simple weather dashboard that uses HTML, CSS, and JavaScript. This will fetch weather data from an external API (like OpenWeatherMap) to display the weather details.

1. HTML (index.html):

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather Dashboard</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="weather-container">
        <h1>Weather Dashboard</h1>
        <div class="search-box">
            <input type="text" id="city-input" placeholder="Enter city name">
            <button onclick="getWeather()">Search</button>
        </div>
        <div id="weather-info">
            <h2 id="city-name"></h2>
            <p id="temp"></p>
            <p id="description"></p>
            <p id="humidity"></p>
            <p id="wind-speed"></p>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>

2. CSS (style.css):

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f3f4f6;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.weather-container {
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    text-align: center;
    width: 300px;
}

.search-box {
    margin-bottom: 20px;
}

#city-input {
    padding: 10px;
    width: 70%;
    margin-right: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

button {
    padding: 10px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}

h2 {
    margin-bottom: 10px;
}

#weather-info p {
    font-size: 16px;
    margin: 5px 0;
}

3. JavaScript (script.js):

const apiKey = 'YOUR_API_KEY'; // Replace with your OpenWeatherMap API key

function getWeather() {
    const city = document.getElementById('city-input').value;
    
    if (city === "") {
        alert("Please enter a city name");
        return;
    }

    const apiUrl = `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${apiKey}&units=metric`;

    fetch(apiUrl)
        .then(response => response.json())
        .then(data => {
            if (data.cod === "404") {
                alert("City not found!");
            } else {
                const cityName = data.name;
                const temp = data.main.temp;
                const description = data.weather[0].description;
                const humidity = data.main.humidity;
                const windSpeed = data.wind.speed;

                document.getElementById('city-name').textContent = cityName;
                document.getElementById('temp').textContent = `Temperature: ${temp}°C`;
                document.getElementById('description').textContent = `Weather: ${description}`;
                document.getElementById('humidity').textContent = `Humidity: ${humidity}%`;
                document.getElementById('wind-speed').textContent = `Wind Speed: ${windSpeed} m/s`;
            }
        })
        .catch(error => {
            alert("Error fetching data. Please try again later.");
        });
}

Instructions:

1. API Key: To use the OpenWeatherMap API, you need to sign up on OpenWeatherMap and get an API key. Replace 'YOUR_API_KEY' in the JavaScript code with the key you get from OpenWeatherMap.


2. Structure: Place the HTML, CSS, and JS files in the same directory.


3. Run: Open the index.html file in your browser to see the weather dashboard.



The weather dashboard will allow you to input a city name, then fetch and display weather data like temperature, weather description, humidity, and wind speed.

