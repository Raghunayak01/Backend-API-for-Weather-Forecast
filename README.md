# Backend-API-for-Weather-Forecast
Weather api
Application Programming Interfaces that provide access to current & historical weather data on a global scale. There are several public weather APIs like OpenWeatherMap API, Dark Sky API, & Visual Crossing Weather API. These REST APIs can be used to build powerful weather apps
# [Prerequisites

- Python
- Requests library
- Openweather API


# ODE EXPLAINATION: ☁☁🔻
1. it will take input(city name) from user and convert it to longitude and latitude
2. it will convert longitude and latitude to time zone and clock.
3. now we will use longitude and latitude in api link to get data from OpenweatherApi . 
4. you can import data like, temperature , climate, wind speed, pressure, cloud, image, humidity and many other things you want.
5. we have use datetime module to get day name .


# Weather API:  https://openweathermap.org


# Screenshots

![2023-11-25 (1)](https://github.com/Raghunayak01/Backend-API-for-Weather-Forecast/assets/150252274/52fcceaa-8e8e-4b01-afc8-0de21c862e1f)
![2023-11-25 (3)](https://github.com/Raghunayak01/Backend-API-for-Weather-Forecast/assets/150252274/172b0417-ed52-404c-98f7-6f42cf665b0a)
![2023-11-25 (4)](https://github.com/Raghunayak01/Backend-API-for-Weather-Forecast/assets/150252274/63abc1a6-4611-4e5a-9fdd-29a8c23d92ae)
![2023-11-25](https://github.com/Raghunayak01/Backend-API-for-Weather-Forecast/assets/150252274/48e194aa-b2e2-45ae-b253-f9858593762b)
![Screenshot (11)](https://github.com/Raghunayak01/Backend-API-for-Weather-Forecast/assets/150252274/e1dbb811-22c2-4ea0-8780-41983dc54dda)
![2023-11-25 (2)](https://github.com/Raghunayak01/Backend-API-for-Weather-Forecast/assets/150252274/7c5cba83-f070-40d0-b25c-514d5315e8f6)

# Additionals
This python script accepts multiple query parameters. The code includes the ability to retrieve weather information for multiple locations through the /weather endpoint.
The code includes try-except blocks to catch and handle exceptions that may occur during API requests or data processing.
Appropriate status codes are returned in the API responses, such as 400 for bad requests, 200 for response and 500 for internal server errors.
