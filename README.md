# Movie Recommendation System

## Overview
This is a Movie Recommendation System built using Python and the Movielens 100k dataset. It uses collaborative filtering techniques like SVD (Singular Value Decomposition) and a hybrid approach (SVD + User-based KNN) to suggest personalized movie recommendations for users. The system includes visualizations, model evaluation, and tuning to enhance performance.

## Features
- **SVD Model**: Predicts movie ratings using latent factor modeling.
- **Hybrid Model**: Combines SVD and User-based KNN for better accuracy.
- **Visualizations**: Includes rating distribution, top recommendations, user-item matrix heatmap, user similarity matrix, and movie clusters (PCA).
- **Evaluation**: Measures RMSE (0.9348), Precision@10 (0.714), and Recall@10 (0.545).
- **Tuning**: Optimized with GridSearchCV (Best RMSE: 0.9423 with n_factors=20, n_epochs=20, lr_all=0.005).

## Technologies Used
- **Languages**: Python
- **Libraries**: pandas, numpy, surprise, matplotlib, seaborn, scikit-learn
- **Environment**: Jupyter Notebook

## Dataset
- **Source**: Movielens 100k[](https://grouplens.org/datasets/movielens/)
- **Details**: Contains 100,000 ratings from 943 users on 1682 movies.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/neelendrashukla/movie-recommendation-system.git