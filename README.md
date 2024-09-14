# Movie-Recommendation-System
This project builds a movie recommendation system using content-based filtering. It recommends movies similar to a user's input by comparing keywords, cast, genres, and directors.

Key Features:
Data Preprocessing: Combines movie features (keywords, cast, genres, and director) into a single string for each movie.
Vectorization: Uses CountVectorizer to convert movie content into numerical data.
Cosine Similarity: Computes similarity scores between movies based on their features.
User Input: The user enters a movie title, and the system recommends the top 5 similar movies.

Libraries:
pandas for data handling.
sklearn for text vectorization and similarity calculation.
