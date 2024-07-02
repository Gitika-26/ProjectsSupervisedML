# Spam-Email-Detection-Using-SVM
Spam Email Detection Using SVM
This repository contains a machine learning project aimed at detecting spam emails using Support Vector Machines (SVM). The model is trained on a dataset containing email data with binary labels indicating whether an email is spam or not. The SVM classifier leverages features extracted from email contents to accurately classify them.

Features
Data Preprocessing: Handles loading, cleaning, and preparing the dataset for training.
Feature Extraction: Uses TF-IDF vectorization to convert email text into numerical features.
Model Training: Implements an SVM classifier to train on the dataset.
Hyperparameter Tuning: Utilizes GridSearchCV for optimizing the SVM hyperparameters.
Model Evaluation: Includes evaluation metrics like accuracy, confusion matrix, and classification report.
Model Persistence: Saves the trained model and vectorizer for future use.
Prediction: Allows for predicting whether a given email is spam or not using the trained model.
 Dataset - emails.csv
