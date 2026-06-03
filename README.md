# Email Spam Detection Using NLP and Machine Learning

## Project Overview

This project is an Email Spam Detection System developed using Python, Natural Language Processing (NLP), and Machine Learning. The system analyzes email or SMS text messages and classifies them as Spam or Ham (Not Spam).

## Features

* Text preprocessing and cleaning
* Stopword removal
* Stemming using Porter Stemmer
* Bag of Words feature extraction
* Spam/Ham classification
* Model accuracy evaluation
* Prediction on custom messages

## Technologies Used

* Python
* Pandas
* NLTK
* Scikit-Learn
* Seaborn
* Matplotlib

## Machine Learning Algorithm

* Multinomial Naive Bayes (MNB)

## Workflow

1. Load dataset
2. Clean and preprocess text
3. Remove stopwords
4. Apply stemming
5. Convert text into numerical features using Bag of Words
6. Split data into training and testing sets
7. Train Multinomial Naive Bayes model
8. Evaluate accuracy
9. Predict whether a message is Spam or Ham

## Results

The model achieves high accuracy in detecting spam messages and can be used as a basic email filtering system.

## Future Enhancements

* Streamlit Web Application
* Flask Deployment
* Deep Learning Models (LSTM/BERT)
* Real-time Email Integration
