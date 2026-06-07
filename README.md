# 🎬 Movie Recommendation System

A Content-Based Movie Recommendation System built using Python, Pandas, Scikit-Learn, and Natural Language Processing (NLP). 
The system recommends movies similar to a selected movie based on genres, keywords, cast, crew, and movie overview.

---

## 📌 Project Overview

This project uses the TMDB 5000 Movies Dataset to build a recommendation engine.

Instead of relying on user ratings, it analyzes movie content and recommends similar movies using:

- Genres
- Keywords
- Cast
- Director
- Movie Overview

The similarity between movies is calculated using **Cosine Similarity** on text features.

---

## 🚀 Features

- Content-Based Filtering
- NLP Text Processing
- Movie Metadata Analysis
- Cosine Similarity Recommendation Engine
- Fast Recommendation Generation
- Pickle Model Serialization for Deployment

---

## 📂 Dataset

Dataset Used:

1. `tmdb_5000_movies.csv`
2. `tmdb_5000_credits.csv`

Source:
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-Learn
- CountVectorizer
- Cosine Similarity
- Pickle

---

## 📊 Workflow

### 1. Import Libraries

```python
import numpy as np
import pandas as pd
