# 🎵 Weather-Based Music Recommendation System

A smart **music recommendation system** that suggests songs based on **current weather conditions** using real-time weather APIs and machine learning techniques.

This project combines **weather data and user preferences** to recommend suitable music that matches the user's mood influenced by the weather.

---

# 📌 Project Overview

Music preferences often change depending on the **weather and mood**. For example:

- 🌧 Rainy weather → Calm / Sad music  
- ☀️ Sunny weather → Energetic / Happy music  
- ❄️ Cold weather → Relaxing music  

This project uses **weather APIs** to fetch real-time weather data and recommends music accordingly using recommendation algorithms.

---

# ⚙️ Technologies Used

- **Python**
- **Machine Learning**
- **REST APIs**
- **Pandas**
- **NumPy**
- **Scikit-learn**

### APIs Used

- **OpenWeather API** – to fetch real-time weather information
- **Music API / Dataset** – to retrieve song data

---

# 🧠 Recommendation Approach

The system uses a combination of:

### 1️⃣ Content-Based Filtering
Recommends songs based on similarity between weather conditions and song attributes.

### 2️⃣ Collaborative Filtering
Uses user preference patterns to suggest songs liked by similar users.

### 3️⃣ Weather Context Integration
Weather conditions are mapped to different music moods.

Example mapping:

| Weather | Recommended Mood |
|--------|----------------|
| Rainy | Calm / Emotional |
| Sunny | Happy / Energetic |
| Cloudy | Relaxing |
| Snowy | Soft / Ambient |

---

# 📂 Project Structure

```
weather-music-recommendation
│
├── dataset
│   └── music_dataset.csv
│
├── src
│   ├── weather_api.py
│   ├── recommendation_model.py
│   └── main.py
│
├── notebooks
│   └── music_recommendation.ipynb
│
├── requirements.txt
│
└── README.md
```

---

# 📊 How the System Works

1️⃣ User enters **city/location**

2️⃣ The system fetches **current weather data** using the weather API.

3️⃣ Weather condition is extracted (Sunny, Rainy, Cloudy, etc.)

4️⃣ Based on the weather condition:
- The recommendation model filters relevant music categories.

5️⃣ The system returns **recommended songs** to the user.

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/weather-music-recommendation.git
```

Navigate to the project folder

```bash
cd weather-music-recommendation
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

Run the main application:

```bash
python main.py
```

Enter your city name when prompted and receive **weather-based music recommendations**.

---

# 📈 Example Output

```
Current Weather: Rainy

Recommended Songs:
1. Someone Like You – Adele
2. Fix You – Coldplay
3. Let Her Go – Passenger
4. Skinny Love – Bon Iver
5. All I Want – Kodaline
```

---

# 🔮 Future Improvements

- Integration with **Spotify API**
- Real-time music streaming
- Personalized user profiles
- Mobile application deployment
- Deep learning based recommendation system

---

# 👩‍💻 Author

**Thumma Manojna Reddy**

AI / ML Enthusiast  
B.Tech CSE (AI & ML)

🔗 GitHub  
https://github.com/thummamanojnareddy  

🔗 LinkedIn  
https://www.linkedin.com/in/manojna-reddy-thumma-536b9730b/

---

⭐ If you found this project helpful, consider **starring the repository**!
