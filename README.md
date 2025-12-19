# 🌾 Digital Krishi Officer 🌾

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-2.3.3-orange?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)

A **full-stack, AI-powered farming assistant** designed for Indian farmers. Provides **crop advice, disease detection, weather alerts, market prices and government schemes** in multiple languages.

---

## 💡 Features

- Ask farming questions via **text** or **voice** input.  
- **Plant image analysis** using AI to detect crop health and suggest treatments.  
- **Local weather forecast** with alerts for extreme conditions.  
- **Crop market price lookup** by state and commodity.  
- **Government schemes** information in multiple languages.  
- **Multilingual support**: English, Hindi, Malayalam, Tamil, Kannada.  

---

## 🛠 Tech Stack

- **Backend:** Python, Flask  
- **Frontend:** HTML, CSS, JavaScript  
- **AI:** Google Gemini API  
- **Data:** CSV for crop prices, JSON for government schemes  
- **APIs:** WeatherAPI for weather data  

---

## ⚡ Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/sarthak-cs/digital-krishi-officer.git
cd digital-krishi-officer
```
2. **Create a virtual environment**
```
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
```
3. **Install dependencies**
```
pip install -r requirements.txt
```
4. **Add API keys**
Copy .env.example to .env and add your keys:
```
GEMINI_API_KEY=your_gemini_api_key_here
WEATHER_API_KEY=your_weather_api_key_here
```
5. **Run the Flask app**
```
python app.py
```
6. **Open in browser**
   Go to ```http://127.0.0.1:5000``` to access the app.

---

## 🔗 Notes
- Maximum plant image size: 5MB
- Supported image types: PNG, JPG, JPEG, GIF, BMP, WebP
- Voice recognition works in Chrome & Edge only

---

## 👨‍💻 Author

### Sarthak Tyagi – CSE Student | Hackathon Participant
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/sarthak_tyagi_cs) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/sarthak-tyagi-cs) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:tsarthak878@gmail.com) 
