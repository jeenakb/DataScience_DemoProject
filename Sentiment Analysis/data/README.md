                                                     Sentiment Analysis using Machine Learning

Purpose:

The purpose of sentiment analysis of product reviews is to automatically understand the opinions, emotions, or attitudes expressed in text data. It is widely used in business, research, and social media to make sense of large amounts of unstructured text. This helps organizations gain actionable insights from customer feedback, improve products or services, and make data-driven decisions.


Project Overview:

This project analyzes Amazon product reviews and predicts the sentiment of each review (positive, neutral, negative) using machine learning algorithms.


 1. Data Analysis & Preprocessing
    - Convert rating to sentiment labels (positive, neutral, negative)  
    - Clean the review text (remove punctuation, lowercase, remove stopwords)  
    - Prepare features (X) and labels (y)  
    - Convert text to numbers using TF-IDF vectorization  
    - Split data into training and testing sets  


 2. ML Algorithms Used for Training
    - Logistic Regression  
    - Naive Bayes  
    - Support Vector Machine (SVM)  
    - Random Forest  


 3. Prediction & Analysis
    - Train each model on the training data  
    - Predict sentiment for the test data  
    - Evaluate performance using accuracy and other metrics  
    - Compare models to determine which gives the best predictions  

Best Accuracy: 0.90 (Random Forest)  


Dataset:
The dataset used in this project is available on Kaggle:  
[Amazon Product Reviews Dataset](https://www.kaggle.com/datasets/yasserh/amazon-product-reviews-dataset?)