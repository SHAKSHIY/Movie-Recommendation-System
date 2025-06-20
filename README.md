# 🎬 Movie Recommendation System

A simple content-based movie recommender built using Python, Pandas, and Scikit-learn. This project uses a movie dataset to suggest similar movies based on metadata like **cast**, **director**, **genres**, and **keywords** using **cosine similarity** over a text feature matrix.

---

## 📌 Overview

This project demonstrates a basic **Content-Based Filtering** recommendation system. Given a movie title (e.g., *Avatar*), the system analyzes movie metadata and returns the top 5 most similar movies from the dataset using **CountVectorizer** and **cosine similarity**.

---

## ✨ Features

- 🧠 Content-based recommendation using movie metadata
- 📚 Uses genres, keywords, cast, and director as content features
- 🔍 Cosine similarity for measuring movie similarity
- 📈 Built entirely with Python and Scikit-learn
- 🖥️ Outputs top 5 similar movies for a given input

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn (`CountVectorizer`, `cosine_similarity`)

---

## 📂 Project Structure

![image](https://github.com/user-attachments/assets/b43af6ed-0b0b-4d27-a3a3-fb1526760a15)


---

## ⚙️ How It Works

1. **Load the Dataset**: The `movie_dataset.csv` contains information about movies.
2. **Select Features**: Use content features – `keywords`, `cast`, `genres`, and `director`.
3. **Preprocessing**: Fill in missing values and combine the selected features into a single string.
4. **Vectorization**: Use `CountVectorizer` to convert text to feature vectors.
5. **Similarity Calculation**: Use `cosine_similarity` to compare movies.
6. **Recommendation**: Given a movie title, the system returns the most similar movies.

---

## 🧪 Sample Output

If a user likes **Avatar**, the system will output:

Top 5 similar movies to Avatar are:

1. Aliens
2. Titanic
3. Guardians of the Galaxy
5. Interstellar
6. The Avengers



---

## 🚀 Getting Started

### 1. Clone the Repository

- git clone https://github.com/SHAKSHIY/Movie-Recommendation-System.git
- cd Movie-Recommendation-System


### 2. Install Requirements
Make sure Python 3 is installed. Then run:

- pip install pandas numpy scikit-learn

### 3. Run the Recommender

- python recommendation.py

Change the value of movie_user_likes in the code to test other movies.

---

## 🙌 Acknowledgments

- Dataset: [movie_dataset.csv] – freely available online

- Scikit-learn documentation for vectorization and similarity concepts

- Educational purpose content-based filtering tutorial inspiration
