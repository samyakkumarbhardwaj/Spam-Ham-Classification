Spam vs Ham Email Classification

This project is a machine learning model that classifies emails as Spam (unwanted messages) or Ham (legitimate messages). It uses Natural Language Processing (NLP) techniques to clean and transform raw email text into numerical features, then trains a Logistic Regression classifier to make predictions.

The dataset (mail_data.csv) contains a collection of emails labeled as spam or ham.

🚀 Project Workflow

Data Loading

Reads email data from mail_data.csv using pandas.

Data Cleaning

Handles missing values.

Encodes labels (ham → 0, spam → 1).

Feature Extraction (NLP)

Uses TF-IDF Vectorizer to convert text into numerical features.

Model Training

Trains a Logistic Regression classifier on the training data.

Model Evaluation

Evaluates performance using accuracy score on test data.

📊 Dataset

File: mail_data.csv

Columns:

Category → ham or spam

Message → email text content

The dataset contains thousands of real email samples commonly used in spam detection research.