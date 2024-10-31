Restaurant Reviews Classification Project

This project is focused on classifying restaurant reviews as positive or negative using Natural Language Processing (NLP) techniques. By implementing a Bag of Words model with a Naive Bayes classifier, we aim to achieve effective text classification and evaluate model accuracy.
Table of Contents

    Project Overview
    Features
    Project Structure
    Installation
    Usage
    Results
    Contributing
    License

Project Overview

The Restaurant Reviews Classification project applies NLP methods to preprocess text and build a machine learning model for sentiment analysis. Using the Bag of Words model, the project transforms textual data into a structured format that can be classified as either positive or negative sentiment.
Features

This project includes:

    Text Preprocessing: Utilizing regular expressions to clean text, removing stopwords, and applying PorterStemmer to standardize word forms.
    Corpus Creation: Building a corpus for text vectorization.
    Bag of Words Model: Using Count Vectorizer to represent the text data as numeric features.
    Classification: Implementing a Naive Bayes classifier for sentiment analysis.
    Evaluation: Analyzing model performance with Confusion Matrix and Accuracy Score.

Project Structure

The main components of this project are as follows:

    Restaurant_Reviews.py - Main script with data loading, preprocessing, and model implementation.
    README.md - Project documentation (this file).
    data/Restaurant_Reviews.csv - Dataset containing restaurant reviews with sentiment labels.

Installation

To run this project, you need Python and the following libraries:

bash

pip install numpy pandas nltk scikit-learn

Usage

    Clone this repository:

    bash

git clone https://github.com/yourusername/restaurant-reviews-classification.git
cd restaurant-reviews-classification

Run the main script:

bash

    python Restaurant_Reviews.py

Results

The Naive Bayes classifier was evaluated on a set of restaurant reviews, with performance measured using:

    Accuracy Score
    Confusion Matrix

These metrics provided insights into the classifier’s effectiveness in categorizing positive and negative reviews.
