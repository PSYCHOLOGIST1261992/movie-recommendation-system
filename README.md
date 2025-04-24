# 🎬 Movie Recommendation System

A content-based movie recommender built using NLP techniques and cosine similarity on the TMDB 5000 Movies dataset.

## 📦 Overview

This project uses movie metadata (genres, overview, cast, keywords, director) to recommend similar movies based on a selected title. It's built entirely in Python and runs smoothly in Google Colab.

---

## 🔧 Features

- Dataset merging and feature engineering (genres, cast, keywords, overview, director)
- Text vectorization using CountVectorizer
- Cosine similarity to find top 5 similar movies
- Simple `recommend()` function to test any movie

---

## 🚀 How to Run It

1. Open the notebook in **Google Colab**
2. Upload the datasets when prompted
3. Run all cells and try:
```python
recommend("Avatar")


⭐️ Star this repo if you like it! Pull requests and feedback are always welcome.

---

Let me know if you want help:
- Publishing this on GitHub
- Adding visuals (screenshots of Colab output)
- Turning this into a **web app with Streamlit**

Ready to ship this to GitHub?
