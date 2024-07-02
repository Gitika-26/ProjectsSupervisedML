# Cat-vs-Dog-Classifier
 
This repository contains code for a machine learning model that classifies images as either cats or dogs using Support Vector Machine (SVM) from scikit-learn and image processing tools from scikit-image.

Features:
Dataset: Images of cats and dogs are loaded from specified directories and preprocessed to a uniform size (64x64 pixels).
Model: SVM classifier is trained using GridSearchCV to find the best hyperparameters (C, gamma, kernel) for optimal performance.
Evaluation: Model accuracy is evaluated on a test set, and the best model is saved for future use.
Prediction: A function is provided to classify new images of cats or dogs based on the trained model.
Requirements:
Python 3.x
scikit-learn
scikit-image
numpy
pickle
Usage:
Dataset Preparation: Organize your cat and dog images into separate directories (Cat and Dog).
Training: Run the provided script to train the SVM classifier and find optimal parameters using GridSearchCV.
Prediction: Use the classify_image function to classify new images after training.
