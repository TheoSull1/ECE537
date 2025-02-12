# ECE537
Sentiment Analysis of Amazon Reviews

Project Overview

This project performs sentiment analysis on Amazon product reviews using Natural Language Processing (NLP) techniques. It employs TF-IDF for feature extraction and multiple machine learning models to classify sentiments as positive or negative. The primary goal is to determine the most effective model for sentiment classification.

Dataset

Source: Amazon product reviews dataset

Preprocessing: Cleaning text, removing stopwords, stemming/lemmatization, tokenization

Label Encoding: Sentiments are labeled as 1 (positive) and 0 (negative)

Methods & Techniques

TF-IDF (Term Frequency-Inverse Document Frequency): Used for feature extraction from text data.

Machine Learning Models:

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

Naïve Bayes Classifier

Neural Networks (if applicable)

Model Evaluation Metrics:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

Installation & Requirements

To run this project locally, install the following dependencies:

pip install pandas numpy scikit-learn nltk matplotlib seaborn

Usage

Run the following command to execute the sentiment analysis:

python sentiment_analysis.py

Results

Model performance comparison based on evaluation metrics

Visualizations of sentiment distribution and model accuracy

Future Improvements

Implement deep learning models (LSTMs, Transformers)

Use word embeddings (Word2Vec, GloVe) instead of TF-IDF

Expand dataset for better generalization

Author

Samuel Bellaire
Theo Sullivan
