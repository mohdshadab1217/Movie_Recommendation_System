### 📽️ Content-Based Movie Recommendation System
This project implements a content-based recommendation system for movies using movie metadata. It analyzes description to recommend similar movies based on user input.


### 📊 Features
Built using pandas, scikit-learn, and NearestNeighbors.

Uses TFIDF vectorization on textual features (e.g., movie descriptions).

Calculates similarity using cosine distance.

Returns the top 5 most similar movies for a given input movie name.


### 📁 Dataset
The dataset used is sourced from Kaggle and includes movie metadata.
Make sure to use the exact movie names as they appear in the dataset for accurate recommendations.


### 🚀 How to Use
Run the notebook to train the model.

Use 'name=df.name[88]' to pick a movie name or manually input one but the name should be exactly same as in dataset. All names should be in lowercase.

Use the similarity function to get recommendations.

The output displays the top similar movies ranked by relevance.
