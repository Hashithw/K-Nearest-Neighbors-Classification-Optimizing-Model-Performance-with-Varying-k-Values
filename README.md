# K-Nearest Neighbors Classification: Optimizing Model Performance with Varying k Values

## Project Overview
In this project, we use the K-Nearest Neighbors (KNN) algorithm to classify data based on various input features. The dataset contains several continuous features, and the goal is to predict the target class (binary classification). This project demonstrates how changing the number of neighbors (k) affects model performance and helps determine the optimal number for prediction accuracy.

## Methods
- Data Exploration: The dataset is first explored using visualizations like pair plots to understand the relationships between features and the target class.

- Feature Scaling: The features are scaled using StandardScaler to standardize the data and ensure that the model performs optimally without being affected by the differing scales of features.

- Model Training: The KNN algorithm is applied with different values of k to train the model. We start by testing with k=1 and then evaluate other values like k=30.

- Model Evaluation: The model's performance is evaluated using classification metrics such as accuracy, confusion matrix, and error rates. We compare the performance of the model for different k-values to find the best configuration.
