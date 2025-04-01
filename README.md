# Spotify_Music_Recommend

# Overview

This project is a Music Recommender System that suggests songs based on their lyrics' similarity using TF-IDF and cosine similarity. It is built using Python, Pandas, Scikit-learn, Spotipy, and Streamlit for deployment.

# Features

Loads a dataset of song lyrics.

Preprocesses text using stemming and tokenization.

Computes TF-IDF vectors for lyrics.

Uses cosine similarity to find similar songs.

Integrates with Spotify API to fetch album covers.

Provides a Streamlit web interface for user interaction.

# Dataset

The dataset used in this project can be downloaded from Kaggle:
Spotify Million Song Dataset

# Technologies Used

Python (Pandas, NLTK, Scikit-learn, Spotipy, Streamlit)

Machine Learning (TF-IDF, Cosine Similarity)

Spotify API (Spotipy for album covers)

Streamlit (Web application deployment)

# Installation

Install dependencies:

pip install -r requirements.txt

Run the Streamlit app:

streamlit run app.py

# Usage

Select a song from the dropdown list.

Click the Show Recommendation button.

The system displays 5 recommended songs along with their album covers.

# Files

spotify_millsongdata.csv - Dataset containing song lyrics.

similarity.pkl - Precomputed similarity matrix (can be obtained by running spotify_music_recommend.ipynb).

df.pkl - Processed dataset for recommendations (can be obtained by running spotify_music_recommend.ipynb).

app.py - Streamlit web app.

# Future Enhancements

Improve text preprocessing (e.g., remove stop words, lemmatization).

Include audio feature-based recommendations.

Add user rating feedback for better recommendations.

# Screenshot
![Screenshot (115)recom](https://github.com/user-attachments/assets/49d48d1b-f3cb-4c80-9add-57e35705f55b)
