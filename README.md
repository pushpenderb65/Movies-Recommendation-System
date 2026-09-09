# Movies Recommendation System

## 📌 Overview
A content-based movie recommendation system that suggests movies based on similarity to user preferences.

## 🎯 Features
- Content-based filtering
- TF-IDF vectorization
- Cosine similarity matching
- Real-time recommendations
- Movie metadata processing

## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn (TF-IDF)
- Streamlit/Flask

## 📂 Project Structure
- `movies.ipynb` - Analysis notebook
- `app.py` & `main.py` - Application files
- `movies_metadata.csv` - Movie dataset
- `tfidf.pkl` - TF-IDF vectorizer
- `tfidf_matrix.pkl` - Pre-computed TF-IDF matrix
- `df.pkl` - Processed dataframe
- `indices.pkl` - Movie indices

## 🚀 Installation
```bash
pip install -r requirements.txt
```

## 💻 Usage
```bash
python app.py
```

## 🎬 How It Works
1. User selects a movie
2. System calculates similarity scores
3. Top recommendations displayed based on content features

## 📊 Dataset
- 5000+ movies with metadata
- Includes: Genre, plot description, cast, ratings
