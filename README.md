Movie Recommendation System (Collaborative Filtering)
This project implements a Movie Recommendation System using the MovieLens 100K dataset. The system is based on Collaborative Filtering, specifically using a K-Nearest Neighbors (KNN) algorithm with cosine similarity. The goal is to recommend movies to users based on their past ratings, and the similarity of movies based on ratings from other users.
Overview:
Dataset: The project uses the MovieLens 100K dataset, which contains 100,000 movie ratings from 943 users for 1,682 movies.
Methodology: This recommendation system employs Collaborative Filtering, a method that relies on user-item interactions. It identifies patterns in ratings by users and recommends movies similar to those a user has rated highly.
Algorithm: The system uses the K-Nearest Neighbors (KNN) algorithm, where the cosine similarity between movies is used to determine how similar they are. The top similar movies to a given movie are recommended to the user.
How It Works:
Data Preprocessing: The dataset is loaded and transformed into a user-item matrix, where each row represents a user, each column represents a movie, and the values represent the ratings given by users.
KNN Model: The user-item matrix is converted into a sparse matrix for memory efficiency, and the KNN algorithm is trained using cosine similarity to find similar movies based on ratings.
Recommendations: Given a movie ID, the system retrieves the top N most similar movies based on user ratings and recommends them to the user.
Collaborative Filtering vs. Content-Based Filtering:
This project uses Collaborative Filtering, not Content-Based Filtering. The key difference is:

Collaborative Filtering: Makes recommendations based on the behavior and preferences of other users (i.e., similarity in ratings between users or movies). This is used in this project.
Content-Based Filtering: Recommends items based on the features of the items themselves (e.g., recommending movies with similar genres or directors).
In this project, the system recommends movies based on the similarity of ratings between movies, which is a classic example of Collaborative Filtering.
