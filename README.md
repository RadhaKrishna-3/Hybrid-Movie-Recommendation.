# Hybrid Movie Recommendation System 🎬
This project implements a **Hybrid Recommendation System** using:
- ✅ Content-Based Filtering (TF-IDF + Cosine Similarity)
- ✅ Collaborative Filtering (SVD from Scikit-Learn)

## 📌 Features
- Recommends movies based on user preferences
- Uses normalized rating matrices
- Combines multiple recommendation techniques

## 🛠️ Technologies Used
- Python 🐍
- Pandas, NumPy, Scikit-Learn 📊

## 🚀 Usage
```python
###Run the recommendation function##
user_id=??
recommend_movies_hybrid(user_id, ratings_matrix, hybrid_ratings, movies)
