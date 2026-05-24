# 🎬 Movie Recommender System

A content-based Movie Recommendation System built using Machine Learning and NLP techniques. This project recommends movies similar to the movie selected by the user.

---

## 🚀 Features

- Recommend similar movies instantly
- Content-based recommendation system
- Movie posters displayed using TMDB API
- Simple and interactive UI using Streamlit
- Fast recommendation generation using cosine similarity

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Streamlit
- Pickle

---

## 📂 Dataset

Dataset used:
- TMDB 5000 Movie Dataset

Files:
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

---

## 🧠 Machine Learning Concepts Used

- Natural Language Processing (NLP)
- Text Vectorization
- Cosine Similarity
- Feature Engineering
- Recommendation Systems

---

## ⚙️ How It Works

1. Movie datasets are merged and cleaned
2. Important features like:
   - genres
   - keywords
   - cast
   - crew
   - overview
   are combined into tags
3. Text data is vectorized using CountVectorizer
4. Cosine similarity is calculated between movies
5. Similar movies are recommended based on similarity score

---

## 📸 Project Demo

### Home Page
(Add screenshot here)

### Recommendation Output
(Add screenshot here)

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/Jay5852/movie-recommender-system.git
