 Twitter Sentiment Analysis using Machine Learning

 Project Overview

This project focuses on analyzing the sentiment of tweets using Machine Learning techniques. The goal is to classify tweets as positive or negative based on their textual content.

The model is trained on the Sentiment140 dataset, which contains 1.6 million tweets labeled for sentiment analysis.

📊 Dataset Information

Dataset Name: Sentiment140

Source: Kaggle

Size: 1.6 Million Tweets

Labels:

0 → Negative

1 → Positive

Features:

Target (sentiment label)

Tweet ID

Date

Query

Username

Tweet Text

⚙️ Technologies Used

Python 

NumPy

Pandas

NLTK (Natural Language Toolkit)

Scikit-learn

Google Colab

🔍 Project Workflow

1. Data Collection

Dataset downloaded using Kaggle API

2. Data Preprocessing

Removed URLs, mentions, and special characters

Converted text to lowercase

Removed stopwords using NLTK

Applied stemming using PorterStemmer

3. Feature Extraction

Converted text data into numerical form using:

TF-IDF Vectorization

4. Model Training

Used Logistic Regression

Split dataset into training and testing sets

5. Model Evaluation

Evaluated using accuracy score

📈 Results
Achieved good accuracy in classifying tweet sentiment

Model performs efficiently on large-scale text data
Achieved good accuracy in classifying tweet sentiment
Model performs efficiently on large-scale text data
