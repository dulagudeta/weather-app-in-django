
# 🌤️ Django Weather App

A real-time weather web application built using **Django**. It allows users to search for any city and view current weather details along with a high-resolution image of that city.

---

## 🚀 Features

- **🌍 Real-time Weather Data**  
  Fetches current temperature, weather conditions, and icons from the [OpenWeatherMap API](https://openweathermap.org/).

- **🏙️ City Image Integration**  
  Automatically displays a beautiful, full-HD image of the searched city using the **Google Custom Search API**.

- **🧭 Location-based Forecast**  
  Provides accurate weather forecasts based on the user's searched city.

- **💡 Intuitive User Interface**  
  Simple and responsive design for a smooth user experience on both desktop and mobile.

---

## 🛠️ Technologies Used

- **Backend:** Django (Python)
- **Frontend:** HTML5, CSS3 
- **APIs:**
  - OpenWeatherMap API
  - Google Custom Search API (for city images)

---

## 🔐 Required API Keys

To run this app, you need the following API keys:

### 1. **OpenWeatherMap API Key**
- Sign up at: https://openweathermap.org/
- Go to your account > API keys and create a key.

### 2. **Google Custom Search API Key**
- Go to: [Google Cloud Console](https://console.cloud.google.com/)
- Create a new project (if needed)
- Enable **Custom Search JSON API**
- Go to "Credentials" > Create API Key

### 3. **Google Custom Search Engine ID (CX)**
- Go to: [Custom Search Engine Control Panel](https://programmablesearchengine.google.com/controlpanel/create)
- Create a new search engine (set "Sites to search" to `www.google.com`)
- After creation, copy the **Search Engine ID**

---

## 📦 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app


2. **Create a Virtual Environment**

   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**

   ```
   pip install -r requirements.txt
   ```

4. **Add Your API Keys**

   Open `weatherapp/views.py` and set:

   ```python
   API_KEY = 'your_google_api_key'
   SEARCH_ENGINE_ID = 'your_google_search_engine_id'
   WEATHER_API_KEY = 'your_openweather_api_key'
   ```



5. **Run the Development Server**

   ```
   python manage.py runserver
   ```

6. **Visit in Your Browser**

   ```
   http://127.0.0.1:8000/
   ```

---

## 🧪 Usage

* Enter a city name in the search bar.
* Click "Check Weather".
* View real-time temperature, weather condition, icon, and a city image.
* If the city is invalid, a helpful error message will be displayed.

---

## 📷 Screenshots

> <img width="1888" height="887" alt="image" src="https://github.com/user-attachments/assets/58f1d755-43f3-4b94-b282-702289d4eb99" />


---

## 🙏 Acknowledgements

* [OpenWeatherMap](https://openweathermap.org/)
* [Google Custom Search JSON API](https://developers.google.com/custom-search/v1/overview)
* Django community

---
Developed by [DULA](https://github.com/dulagudeta)
