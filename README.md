# Spam Mail Detection

This project demonstrates a machine learning approach to detecting spam emails using Logistic Regression. The dataset is preprocessed, feature-engineered, and classified to differentiate between spam and non-spam (ham) emails.

# Features
Dataset: A labeled dataset with categories ham and spam containing 5,572 email messages.
Preprocessing:
Unnecessary columns dropped.
Missing values replaced with empty strings.
Labels encoded (spam = 1, ham = 0).
Text Feature Extraction: Utilizes TF-IDF Vectorizer for transforming text data into numerical features, with options to:
Remove stop words.
Convert all text to lowercase for consistency.
Model Training: Logistic Regression algorithm is employed for classification, achieving high accuracy:
Training Accuracy: 96.6%
Test Accuracy: 96.2%.
Predictive System: A simple system to input text and classify it as spam or ham.
