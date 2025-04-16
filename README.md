# Weather-App

A simple and beautiful Weather Web App built with HTML,CSS,and JavaScript that show current weather
and also 5-day forecast using the OpenWeatherMap API.

![Screenshot 2025-04-12 011839](https://github.com/user-attachments/assets/8ab89c2d-8fda-49ae-8a7e-e45561fead83)


🚀 Features

🔍 Search weather by city name  
🌡️ Shows current temperature, humidity, wind speed, and weather condition  
📅 Shows current date  
📆 5-day forecast (12:00 PM daily snapshot)  
🎨 Responsive design 
❌ Shows "not found" message for invalid city names



🛠️ Tech Stack

.HTML :
         1.  used for layout of the app.
         2. created sections for:
            . Search bar
            . Current weather details 
            . 5- day forecast
            . Error messages if city is not found!!
         3. Used semantic tags like section,div,h1,button.
      
.CSS :
      1. used for design purpose.
      2. Applied gradient backgrounds,layouts and icons.
      3. Style buttons,search bar, and animations for better user experience.
      
.JavaScript :
               1. Intergrated OpenWeatherMap API for getting real-time       
                  weather data.
               2. Used Fetch() to get:
                  . Current weather
                  . 5-day forecast at 12:00 PM
               3. Display icons based on weather condition using condition id.
               4. Handle user input.
               
🌐 OpenWeatherMap API 
                     1. Fetch real-time weather data based on user input(City-Name).
                     2. Use own API key for fetching real-time weather. 
                     3. Give accurate temperature,condition,wind,and humidity.
                     4. 5- day forecast with weather icons.

🧪 How to Use
1. Clone the repo:
   git clone https://github.com/artwithtannu/Weather-App.git

2. Open the project in a code editor.
3. Replace apiKey in script.js with your own OpenWeatherMap API key
4. Open index.html in your browser.

If you enter Correct city name then you get information like that:
![Screenshot 2025-04-12 011850](https://github.com/user-attachments/assets/f5218277-f5ba-44f9-a85f-a115ba3f4132)

![Screenshot 2025-04-16 152444](https://github.com/user-attachments/assets/db446f17-dad5-464b-a45c-41aba7846e62)



