# Stream-Verse

🎬🎵 Movie, Series & Music Recommendation System
Built with Machine Learning • Python • Streamlit GUI • TMDB & Spotify API

This project is an intelligent recommendation system that suggests movies, TV series, and music based on user input. It uses ML similarity algorithms, integrates real-time data from external APIs, and provides an interactive Streamlit-based GUI.

📌 Features
✅ Movie Recommendation

Suggests top 5 similar movies

Uses cosine similarity matrix

Fetches posters dynamically using TMDB API

Displays results in a 5-card responsive layout

✅ Music Recommendation

Recommends similar songs based on metadata & ML similarity

Fetches album covers using Spotify API

Displays album art + song name in clean UI

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

🖼️ Screenshots (Optional – Add After Deployment)
[ Movie Selection Dropdown ]
[ Recommended Movies Grid ]
[ Music Recommendation Grid ]

📊 Dataset Files
File	Purpose
df.pkl	Music dataset
similarity1.pkl	Music similarity matrix
movies_dict.pkl	Movie info dataset
similarity.pkl	Movie similarity matrix
📝 Future Improvements

Add TV series recommendation based on seasons/genres

Add user login system

Add rating-based collaborative filtering

Add multilingual UI support

Deploy using Streamlit Cloud or Render

🤝 Contributing

Pull requests are welcome!
For major changes, open an issue first to discuss proposed modifications.

📜 License

This project is licensed under the MIT License.

If you want, I can also create:

✅ requirements.txt
✅ A project logo/banner
✅ A deploy-ready version for Streamlit Cloud
✅ A professional project abstract for resume

Just tell me!

Sources
give again better readme md file  also the description and project name is stream verse

Here is an improved, more polished README.md with better structure, richer formatting, and professional wording.
The project name is updated to StreamVerse and the description is refined for GitHub-level presentation.

🌌 StreamVerse – Unified Movie, Series & Music Recommendation System
AI-powered recommendations • Streamlit GUI • TMDB + Spotify API Integration

StreamVerse is a smart content recommendation platform that combines movies, web-series, and music into a single interactive system. Built using Machine Learning, Python, and Streamlit, it analyzes similarity scores to recommend the most relevant content based on a user’s input. It also integrates with TMDB for movie posters and Spotify API for real-time album art retrieval.

StreamVerse delivers a smooth, user-friendly interface that displays recommendations visually with posters, song covers, and titles—making it feel like a personalized streaming dashboard.

🚀 Key Features
🎬 Movie & Series Recommendations

Suggests top 5 similar movies/series

Uses cosine similarity and vector-based similarity mapping

Fetches HD posters through TMDB API

Clean, 5-column responsive layout

🎵 Music Recommendation Engine

Recommends songs based on metadata & ML similarity

Fetches album art dynamically using Spotify API

Displays results in a modern card-based layout

🖥️ Streamlit User Interface

Minimal, fast, and interactive UI

Dropdown search for movies and songs

Instant visual results with images + labels

📦 Offline + API Hybrid System

ML models run locally using similarity matrices

Posters and album covers fetched online for real-time visuals

📂 Project Structure
StreamVerse/
│── app.py
│── movie_recommender_system.ipynb
│── musicreccomendation.ipynb
│── df.pkl
│── similarity.pkl
│── similarity1.pkl
│── movies_dict.pkl
│── requirements.txt
│── README.md

🧠 Tech Stack
Layer	Technology
Programming	Python
ML Models	Cosine Similarity, Vector Embedding
Data Libraries	Pandas, NumPy, Pickle
GUI	Streamlit
APIs Used	TMDB, Spotify
Deployment	Local / Streamlit Cloud
📥 Installation Guide
1️⃣ Clone the repository
git clone https://github.com/yourusername/streamverse.git
cd streamverse

2️⃣ Install requirements
pip install -r requirements.txt

🔑 API Configuration
TMDB API Key

Create account: https://www.themoviedb.org

Replace API key in app.py:

api_key = "YOUR_TMDB_API_KEY"

Spotify API Credentials

Register at: https://developer.spotify.com/dashboard

Replace credentials in code:

CLIENT_ID = "YOUR_SPOTIFY_CLIENT_ID"
CLIENT_SECRET = "YOUR_SPOTIFY_CLIENT_SECRET"

▶️ Run the Application
streamlit run app.py


It will open automatically in your browser at:

http://localhost:8501

⚙️ How It Works
🧩 Movie Recommendation Logic

Load movie metadata & similarity matrix

Identify selected movie index

Sort similarity scores

Fetch posters from TMDB

Display in visual grid

🎧 Music Recommendation Logic

Load music data and similarity vectors

Retrieve top 5 matches

Query Spotify API for album artwork

Display songs + covers

🖼️ UI Preview

(Add your screenshots here after deployment)

[ Dropdown Menu ]
[ Movie Poster Grid ]
[ Music Recommendation Cards ]

📊 Dataset Breakdown
File	Description
df.pkl	Music dataset
similarity1.pkl	Music similarity matrix
movies_dict.pkl	Movie dataset
similarity.pkl	Movie similarity matrix
🚀 Future Enhancements

Add genre-based filtering

Add user login + preferences

Add TV show recommendation engine

Add multi-language UI

Deploy on Streamlit Cloud / Render / AWS

Implement Collaborative Filtering

🤝 Contributing

Contributions are always welcome!
Create a pull request or open an issue to suggest improvements.

📜 License

This project is licensed under the MIT License.
