# Weather-Forecast

A web app that predicts real-time weather with AI and API integration.

# Description

Weather Forecast is a web-based platform that predicts real-time weather conditions using AI algorithms such as K-Nearest Neighbors and Gaussian Naive Bayes. The system integrates OpenWeatherMap API to provide accurate data including temperature, humidity, wind speed, and weather descriptions. Users can input a city or country and receive predictions for the next 5 hours. The project addresses climate uncertainty issues that impact agriculture, transportation, and daily decision-making. It demonstrates research skills, problem understanding, and logical reasoning through the integration of Django, REST API, and machine learning models.

# Features

- Display current weather information:
  - Temperature (°C)  
  - Humidity (%)  
  - Wind speed (m/s)  
  - Air pressure (hPa)  
  - Weather description (rain, sunny, cloudy, etc.)
- Predicts weather up to **5 hours ahead** using **Random Forest, KNN, and Gaussian Naive Bayes**
- City/country input via **search box**
- User-friendly web interface built with **Django**
- Integrated with **OpenWeatherMap API**

# Technologies Used

- **Backend**: Django, REST API  
- **Frontend**: HTML, CSS  
- **Machine Learning**: K-Nearest Neighbors (KNN), Gaussian Naive Bayes  
- **API**: [OpenWeatherMap](https://openweathermap.org/api)

# How to Run The Program

1. Clone the repository
git clone https://github.com/username/Weather.git <br>
cd Weather<br>
2. Create a virtual environment
python -m venv myvenv<br>
3. Activate the virtual environment
Windows:<br>
.\myvenv\Scripts\activate<br>
4. Install dependencies
pip install -r requirements.txt<br>
pip install django requests pandas scikit-learn (if requirements.txt is missing)<br>
5. Navigate to Django project folder
cd weatherProject<br>
6. Run the server
python manage.py runserver<br>
7. Enter the city or country name in the Search box
8. View current weather information on the left panel
9. Check detailed weather info (location, time, wind, pressure, visibility, max/min temp) in the center panel
10. See the 5-hour weather forecast displayed at the bottom

# Program Output

The output obtained is a real-time weather report for the requested city or country, along with a 5-hour forecast.
