# Email Spam Classification System

This program describes the implementation of a machine learning- based email classification system using Python. The system uses the Naive Bayes algorithm to determine whether an email is spam or not. The development process uses data from a set of emails to train the model, evaluate its quality, and predict the status of new emails.
# Dataset
The dataset is automatically downloaded from Kaggle using kagglehub: https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv

The dataset contains 5172 rows and 3002 columns. The first column contains the email names. The last column contains the prediction labels: 1 — spam, 0 — not spam. The remaining 3000 columns represent the frequencies of the 3000 most common words from all emails after removing non-alphabetic characters and words.

# Implementation details
Model: Naive Bayes classifier method is used, which analyzes the probabilities of words and is trained on the data.
Predictions and model quality assessment: 
- Confusion Matrix: Displays the counts of true positives, true negatives, false positives, and false negatives to evaluate model performance.
- Classification Report: Generates a report on key metrics (accuracy, recall and F1-Score)
- F1 Score: is the harmonic mean between precision and recall, used to evaluate the quality of binary classifications.
- 
