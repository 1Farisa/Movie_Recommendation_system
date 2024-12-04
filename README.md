# **Movie Recommendation System using KNN**

## **Project Overview**
This project implements a **movie recommendation system** using the **MovieLens 100K dataset**, a widely used dataset for research in recommendation systems. The system utilizes a **K-Nearest Neighbors (KNN)** algorithm with **cosine similarity** to recommend movies similar to a given movie based on user ratings.

## **Key Features**
- Uses **collaborative filtering** to recommend movies.
- Implements a **KNN-based model** for finding similar movies based on user-item interactions.
- Includes functions to retrieve human-readable movie titles for better interpretability.
- Provides visualizations for:
  - Distribution of movie ratings.
  - User-movie interaction heatmaps.
  - Recommendations in a graphical format.

## **About the Dataset**
- **Source:** [MovieLens 100K Dataset on Kaggle](https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset)
- **Details:**
  - Contains **100,000 ratings** from **943 users** for **1,682 movies**.
  - Ratings are on a scale of 1 to 5.
  - Includes additional metadata such as movie titles and genres.

## **Recommendation Type**
This project is based on **collaborative filtering**, specifically **item-based collaborative filtering**:
- **Why Collaborative Filtering?**
  - The system uses user rating data to identify movies similar to a given movie.
  - It relies on the similarity between movies based on the preferences of users who rated them.
- **Why Not Content-Based Filtering?**
  - This project does not consider the attributes or metadata (e.g., genres, directors, etc.) of movies for recommendations.
  - The focus is entirely on user-item interaction data.

## **Technologies Used**
- **Python**: Core language for implementation.
- **Pandas**: For data manipulation and preprocessing.
- **NumPy**: For efficient numerical operations.
- **SciPy**: For sparse matrix representation.
- **Scikit-learn**: For the KNN model.
- **Matplotlib & Seaborn**: For data visualization.

