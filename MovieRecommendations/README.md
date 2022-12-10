# Movie Recommendations

## 1. Problem Statement

Build a movies recommendation system to recommend relevant movies to users based on their historical interactions 

## 2. Data Description

The ratings dataset contains the following attributes:

* Number of observations  - 100004
* Number of variables/columns - 4 (all numeric values )
* nulls - 0

## 3. Modelling Algorithms

- a.  Knowledge/Rank based recommendation system
- b.  User Similarity-Based Collaborative filtering
- c   Item Similarity-Based Collaborative filtering
- d.  Matrix Factorization Based Collaborative Filtering

*Metrics* - As the target variable is categorical, accurracy_score, f1_socre, precision_socre, and recall_score were used.

## 4. Results

Singular Value Decomposition (SVD) **svd_algo_optimized** may be considered as the best performing model for this dataset.	

Its performance metrics are:

1. RMSE: 0.899653
2. Precision = 0.732 & Recall = 0.526 at K = 10 (Top 10 recommendations)

**Rank-Based Recommendation System** is a good model for all new users who haven’t had interactions with the system yet. And it can coexist with the **svd_algo_optimized** in production environment


![rmse](https://github.com/giomvp/AcademicProjects/blob/3984a9c2c5d52119c461e9d9cc3a5222746630c9/MovieRecommendations/imgs/rmse_plt.jpg)

Complete model selection analysis [here](https://github.com/giomvp/AcademicProjects/blob/910adbfc1b250c028b955f266a0111789c0e81bd/MovieRecommendations/MovieRecommendations.ipynb).
