# Stream-Verse

🎬🎵 Movie, Series & Music Recommendation System
Built with Machine Learning • Python • Streamlit GUI • TMDB & Spotify API

This project is an intelligent recommendation system that suggests movies, TV series, and music based on user input. It uses ML similarity algorithms, integrates real-time data from external APIs, and provides an interactive Streamlit-based GUI.

📌 Features

✅ Movie Recommendation

1.Suggests top 5 similar movies

2.Uses cosine similarity matrix

3.Fetches posters dynamically using TMDB API

4.Displays results in a 5-card responsive layout

✅ Music Recommendation

1.Recommends similar songs based on metadata & ML similarity

2.Fetches album covers using Spotify API

2.Displays album art + song name in clean UI

✅ Streamlit GUI

Simple and clean interface

Dropdown selection for movie/music

Real-time results displayed as images + labels

📂 Project Structure

📁 Movie-Music-Recommender/
│── app.py
│── movie_recommender_system.py.ipynb
│── musicreccomendation.ipynb
│── df.pkl
│── similarity.pkl
│── similarity1.pkl
│── movies_dict.pkl
│── requirements.txt
│── README.md

🚀 Tech Stack

Component	Technology
Backend	Python
ML Model	Cosine Similarity + Vectorization
APIs	TMDB API, Spotify API
Frontend	Streamlit
Data Handling	Pandas
Models Storage	pickle

📥 Installation

1️⃣ Clone this repository
git clone https://github.com/yourusername/movie-music-recommender.git
cd movie-music-recommender

2️⃣ Install dependencies
pip install -r requirements.txt

🔑 API Keys Setup
TMDB API

Create an account here: https://www.themoviedb.org

Get your API key and replace it in the code:

api_key = "YOUR_TMDB_API_KEY"

Spotify API

Go to: https://developer.spotify.com/dashboard

Replace with your credentials in the code: 

appy

CLIENT_ID = "YOUR_SPOTIFY_CLIENT_ID"
CLIENT_SECRET = "YOUR_SPOTIFY_CLIENT_SECRET"

▶️ Run the Application
streamlit run app.py


Your web app will open in your browser at:

http://localhost:8501

💡 How It Works
🎬 Movie Recommender Logic

Loads movie vectors and similarity matrix from pickle files

Finds the movie index

Sorts similarity scores

Fetches posters from TMDB

🎵 Music Recommender Logic

Vector-based similarity search

Finds top 5 closest matches

Fetches album cover using Spotify API search


🤝 Contributing

Pull requests are welcome!

________________________________________
Author
Harsh Kumar
Computer Science | Data Analytics | Machine Learning

For major changes, open an issue first to discuss proposed modificat
