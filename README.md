# Movie Recommendation System Using Collaborative Filtering

This project demonstrates the creation of a **Movie Recommendation System** using **collaborative filtering** techniques. It analyzes user-movie rating data and provides personalized movie recommendations based on user preferences and the preferences of similar users.

---

## **Table of Contents**
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Methodology](#methodology)
4. [Technologies Used](#technologies-used)
5. [Results](#results)
6. [Future Work](#future-work)

---

## **Introduction**
In today's digital world, recommendation systems are a crucial tool for improving user engagement on streaming platforms. This project focuses on building a user-based collaborative filtering recommendation system to suggest movies that users are likely to enjoy.

---

## **Dataset**
The project uses the **MovieLens Dataset**, which contains:
- User ratings for movies.
- Metadata about movies, such as titles and genres.

For more information about the dataset, visit the [MovieLens website](https://grouplens.org/datasets/movielens/).

---

## **Methodology**
1. **User-Item Matrix**: Created a matrix where rows represent users, columns represent movies, and values represent ratings.
2. **Handling Missing Data**: Filled missing ratings with default values (e.g., `0`).
3. **Cosine Similarity**: Computed user-user similarity to identify users with similar preferences.
4. **Recommendation Engine**: Predicted movies for a target user based on the preferences of similar users.

---

## **Technologies Used**
- **Python**: Programming language.
- **Pandas**: For data manipulation.
- **NumPy**: For numerical computations.
- **scikit-learn**: To compute cosine similarity.
- **Matplotlib/Seaborn**: For data visualizations.
- **Excel** : For Cleaning and Formatting Data 

---

## **Results**
- Successfully recommended personalized movies for users based on their historical preferences.
- Demonstrated how collaborative filtering provides accurate and scalable solutions for recommendation systems.

---

## **Future Work**
- Add **item-based collaborative filtering** for a more comprehensive recommendation system.
- Incorporate **demographic data** for better personalization.
- Experiment with hybrid recommendation models (e.g., combining content-based and collaborative filtering).

---
