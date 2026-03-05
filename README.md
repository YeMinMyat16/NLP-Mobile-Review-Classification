📱 NLP Mobile Review Classification
📌 Project Description

This project uses Natural Language Processing (NLP) and Machine Learning techniques to analyze customer reviews from the Amazon Unlocked Mobile Reviews dataset.

The system processes textual review data and classifies the mobile phone brand based on the review content.

This project demonstrates a complete NLP pipeline, including:

Text preprocessing

Feature extraction using TF-IDF

Model training

Model evaluation

🎯 Objectives

Clean and preprocess textual review data

Convert text data into numerical features

Train machine learning models for classification

Evaluate model performance using standard metrics

📂 Dataset

Dataset used: Amazon Unlocked Mobile Reviews

Features used in this project:

Brand Name – Mobile brand

Rating – Customer rating

Review Text – Customer written review

Selected brands for this project:

Apple

Samsung

OnePlus

Xiaomi

⚙️ Data Preprocessing

The following preprocessing techniques were applied:

Removing missing values

Filtering selected brands

Tokenization

Stopword removal

Lemmatization using NLTK WordNet Lemmatizer

These steps help improve model performance by reducing noise in the text data.

🔎 Feature Extraction

Text data was converted into numerical vectors using:

TF-IDF (Term Frequency – Inverse Document Frequency)

TF-IDF measures the importance of words in a document relative to the dataset.

🤖 Machine Learning Models
1️⃣ Naive Bayes

Multinomial Naive Bayes classifier

Commonly used in text classification

2️⃣ Logistic Regression

Linear classification model

Effective for multi-class classification problems

📊 Model Evaluation

The models were evaluated using:

Accuracy Score

Classification Report

Confusion Matrix

Results were visualized using Matplotlib and Seaborn.

🛠 Technologies Used

Python

Pandas

NumPy

NLTK

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook
