Overview

This repository contains two machine learning projects implemented in Python using Jupyter Notebooks:

Spam Mail Detection (Classification)

House Price Prediction (Regression)

Both notebooks demonstrate complete ML workflows including preprocessing, model training, evaluation, and custom prediction functions.

1. Spam Mail Detector
Description

A text-classification model that identifies whether an email/message is Spam or Ham using TF-IDF vectorization and a Multinomial Naive Bayes classifier.

Key Steps

Load dataset (CSV uploaded via Colab)

Text preprocessing: lowercasing, regex cleaning, stopword removal

Convert text to numerical features using TfidfVectorizer

Split dataset into training and testing sets

Train Multinomial Naive Bayes classifier

Evaluate using Accuracy, Precision, and F1-Score

Provide a function to predict whether a custom message is spam

2. House Price Predictor
Description

A regression model built using Linear Regression to estimate house prices from numerical housing attributes.

Key Steps

Load dataset and select required numeric columns

Handle missing values

Standardize numerical features using StandardScaler

Split into training and testing sets

Train Linear Regression model

Evaluate using MSE and R² Score

Provide a function to predict price from user-supplied feature values

How to Run
Option 1: Jupyter Notebook (Local)

Clone the repository:

git clone https://github.com/your-username/your-repo.git
cd your-repo


Install dependencies:

pip install -r requirements.txt


Launch Jupyter Notebook:

jupyter notebook


Open the notebook:

spam_mail_detector.ipynb

house_price_predictor.ipynb

Run all cells and upload your dataset when prompted.

Option 2: Google Colab

Open the notebook file in Google Colab

Upload the CSV file when the notebook requests it

Run all cells sequentially
