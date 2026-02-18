
# Movie Recommender System

This project is a content-based movie recommendation system that suggests similar movies based on user selection. The application provides personalized recommendations along with movie posters through an interactive web interface.

---

## Overview

The objective of this project is to build a recommendation system that helps users discover movies similar to their preferences. The system analyzes movie features and similarity scores to recommend the top matching movies.

The application is deployed using Streamlit and fetches movie posters using the TMDB API. 

---

## Features

* Select a movie and get top 5 similar recommendations
* Displays movie posters for better user experience
* Fast similarity-based recommendations
* Interactive and user-friendly interface

---

## How It Works

1. Movie data is preprocessed and stored in a dictionary
2. A similarity matrix is created to measure movie similarity
3. When a user selects a movie:

   * The system finds the most similar movies
   * Top 5 recommendations are returned
4. Posters are fetched dynamically using TMDB API

---

## Tech Stack

* Python
* Pandas
* Streamlit
* Pickle
* TMDB API

---

## Project Structure

```
movie-recommender/
│
├── app.py
├── movie recommender.ipynb
├── movie_dict.pkl
├── similarity.pkl
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## Use Cases

* Personalized movie suggestions
* Content discovery based on preferences
* Entertainment recommendation platforms

---

## Author

Snehal Budale
Final Year Engineering Student | AI & Data Science

---
