# Twitter-Analysis-ML
Twitter Sentiment Analysis  
# Twitter Sentiment Analysis

## Authors
Jeremiah Geisterfer & Quincy Meisman

## Project Overview
This project performs sentiment analysis on a Twitter dataset using three machine learning models: 
- Support Vector Machines (SVM)
- Random Forest Classifier
- Gradient Boosting Classifier

The project explores preprocessing techniques such as:
- Lemmatization
- Term Frequency-Inverse Document Frequency (TF-IDF)

We aim to optimize each model through sample size reduction, feature selection, and hyperparameter tuning. The results are compared across different configurations of the data to evaluate their impact on model accuracy and runtime.

## Features
- Data exploration and visualization
- Preprocessing with lemmatization and TF-IDF
- Baseline performance evaluation
- Sample size optimization
- Feature selection using Recursive Feature Elimination (RFE)
- Hyperparameter tuning with GridSearchCV
- Comparative analysis of model performance

## Data Description
The dataset contains the following fields:
1. **Twitter ID**: Unique identifier for each post.
2. **Category**: One of 32 topics (e.g., popular games, large companies).
3. **Message Text**: The text of the Twitter post.
4. **Sentiment**: Classified as Positive, Negative, Neutral, or Irrelevant.

## Requirements
To run the notebook, you need the following dependencies installed:
- Python (3.8 or higher)
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `nltk`
- `scipy`

