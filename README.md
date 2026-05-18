# 🎬 Movie Recommendation System

A machine learning-based movie recommendation system that suggests similar movies using content-based filtering and cosine similarity. Built with Python and Streamlit.

---

## 🚀 Features

- Recommend movies based on similarity
- Interactive Streamlit web interface
- Displays movie posters using TMDB API
- Content-based recommendation system
- Fast and simple user experience

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- TMDB API
- Pickle

---

## 📂 Project Structure

```plaintext
movie_recommendation_system/
│
├── app.py
├── movie_recommender.ipynb
├── movie_dict.pkl
├── requirements.txt
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/Likhitareddy17/movie_reccomendation_system.git
```

### Navigate to project folder

```bash
cd movie_reccomendation_system
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the Streamlit app

```bash
streamlit run app.py
```

---

## 🧠 How It Works

This project uses a content-based recommendation system.

- Movie metadata such as genres, keywords, cast, and crew are combined
- Text vectorization techniques are applied
- Cosine similarity is used to find similar movies
- Recommended movies are displayed with posters fetched using the TMDB API

---

## 🔑 Environment Variables

Create a `.env` file and add your TMDB API key:

```env
API_KEY=your_api_key_here
```

---

## 📌 Future Improvements

- Add hybrid recommendation system
- Deploy online with Streamlit Cloud
- Add movie search autocomplete
- Improve UI/UX
- Add user authentication

---
