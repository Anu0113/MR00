# Movie Recommendation System

A content-based movie recommendation web application that suggests similar movies based on the movie selected by the user. The system uses movie information such as genres, keywords, cast, crew, and overview to calculate similarity between movies.

The application is built using Python, machine learning, and Streamlit.

## Features

- Select a movie from the available movie list
- Recommends five similar movies
- Displays movie posters with recommendations
- Uses content-based filtering
- Calculates movie similarity using cosine similarity
- Provides a simple and interactive Streamlit interface

## Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing
- CountVectorizer
- Cosine Similarity
- Pickle
- TMDB API
- Requests

## Dataset

The project uses the TMDB 5000 Movie Dataset, which contains information about movies such as:

- Movie title
- Overview
- Genres
- Keywords
- Cast
- Crew
- Movie ID

The main dataset files used are:

```text
tmdb_5000_movies.csv
tmdb_5000_credits.csv
