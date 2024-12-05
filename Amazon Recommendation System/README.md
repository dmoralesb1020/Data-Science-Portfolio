# Amazon Recommendation System 

## Introduction

Recommendation systems have become essential for businesses to enhance user engagement and drive sales. By providing personalized and relevant product suggestions, these systems help consumers navigate the overwhelming number of choices available online.

Amazon employs techniques like item-to-item collaborative filtering to analyze user behavior and generate high-quality, real-time suggestions, significantly enhancing the personalization of its platform.

In this project, I built a recommendation system to suggest products to customers based on their previous ratings of other items. Using a dataset of labeled Amazon product reviews, the objective was to extract meaningful insights and develop a system that enhances the online shopping experience through personalized recommendations.

## Data Description

The Amazon dataset contains the following attributes:

* userId: Every user identified with a unique id
* productId: Every product identified with a unique id
* Rating: The rating of the corresponding product by the corresponding user
* timestamp: Time of the rating. We will not use this column on this project

## Project Overview

This project focuses on building a product recommendation system for Amazon using a dataset of user ratings for electronic products. The goal was to predict the ratings of products a user has not yet interacted with, allowing the system to offer personalized recommendations.

The complete code along with the conclusions are available in the [Jupyter notebook](https://github.com/dmoralesb1020/Data-Science-Portfolio/blob/main/Potential-customers-prediction/Potential_Customers_Prediction_with_Decision_Trees.ipynb). Below are the steps I undertook during this project:

1.	**Data Collection and Preparation:** The dataset was loaded, cleaned, and preprocessed. 
2.	**Exploratory Data Analysis:** Summary statistics, data distributions, and missing values were analyzed. 
3.	**Rank-Based Recommendation:** A popularity-based system was implemented as a baseline, recommending products based on their average rating and popularity.
4.	**Collaborative Filtering:** This approach leveraged user-item interactions to predict ratings. User-user and item-item similarity-based collaborative filtering models were built and evaluated.
5.	**Model-Based Collaborative Filtering:** Matrix factorization using Singular Value Decomposition (SVD) was implemented to address the limitations of similarity-based models. 
6.	**Hyperparameter Tuning:** Each model's hyperparameters were fine-tuned using Grid Search with cross-validation to optimize their performance. 
7.	**Evaluation and Comparison:** The performance of each model was compared using various metrics like RMSE, precision, recall, and F1-score. The SVD model achieved the lowest RMSE and the highest F1-score.
