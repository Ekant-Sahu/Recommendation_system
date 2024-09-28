# Movie Recommender System

## Project Overview

This project is a **Movie Recommender System** that suggests movies based on the similarity of the movie selected by the user. The system utilizes **Streamlit** for the web interface and makes use of **The Movie Database (TMDb)** API to fetch movie posters.

### Key Features:
- User can select a movie from a list.
- The system returns 5 movie recommendations based on similarity to the selected movie.
- Movie posters are displayed alongside the recommendations.

---

## Project Structure

- **`app.py`**: The main application script, which runs the Streamlit app, handles user input, and displays the recommendations with corresponding movie posters.
- **Model Files**: 
  - `movie_list.pkl`: Contains the list of movie titles and corresponding movie IDs.
  - `similarity.pkl`: Precomputed similarity matrix based on the content of movies.

---

## Installation Instructions

### Requirements:
To run the project locally, you need to have the following installed:
- Python 3.7+
- `streamlit`
- `requests`
- `pickle`
- An API key from [TMDb](https://www.themoviedb.org/).

### Steps to Set Up the Project:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Ekant-sahu/Recommendation_system.git
   cd Recommendation_system
