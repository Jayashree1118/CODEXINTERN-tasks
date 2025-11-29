# Overview
This repository contains two machine learning projects implemented in Python using Jupyter Notebooks:

- **Spam Mail Detection** (Classification)
- **House Price Prediction** (Regression)

Both notebooks include preprocessing, model training, evaluation, and custom prediction functions.

---

## 1. Spam Mail Detector

### Description
A text-classification model that determines whether an email or message is **Spam** or **Ham** using TF-IDF vectorization and a Multinomial Naive Bayes classifier.

### Key Steps
- Load dataset (CSV uploaded via Colab)
- Perform text preprocessing: lowercasing, regex cleaning, stopword removal
- Convert text to numerical features using `TfidfVectorizer`
- Split dataset into training and testing sets
- Train a Multinomial Naive Bayes classifier
- Evaluate using Accuracy, Precision, and F1-Score
- Use a custom function to predict whether a message is spam

---

## 2. House Price Predictor

### Description
A regression model developed using Linear Regression to estimate house prices based on numerical housing attributes.

### Key Steps
- Load dataset and select relevant numeric columns
- Handle missing values
- Standardize features using `StandardScaler`
- Split dataset into training and testing sets
- Train the Linear Regression model
- Evaluate using Mean Squared Error (MSE) and R² Score
- Provide a function to generate predictions from user-supplied feature values

---
## How to Run

### Option 1: Run Locally (Jupyter Notebook)

1. Install required dependencies:
   ```bash
   pip install -r requirements.txt
### Launch Jupyter Notebook
- Run the following command:
  - `jupyter notebook`

### Open the notebook files
- `spam_mail_detector.ipynb`
- `house_price_predictor.ipynb`

### Run the project
- Run all cells and upload your dataset when prompted.

---

### Option 2: Run on Google Colab
- Open the notebook in Google Colab.
- Upload the CSV file when requested.
- Run all cells in order.
