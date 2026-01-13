  # Sentiment Analysis Web Application


A Flask-based web application that predicts the sentiment of user-provided text using a pre-trained machine learning model. The app cleans and vectorizes input text before classifying it as positive or negative sentiment.


 # Features

Web-based user interface for sentiment prediction

Text preprocessing (cleaning and normalization)

Pre-trained ML model integration using pickle

Fast and lightweight Flask backend

Simple and clean project structure

# HOW IT WORKS 

User submits text via a web form

Text is cleaned using regex-based preprocessing

Cleaned text is transformed using a saved vectorizer

A trained sentiment analysis model predicts the sentiment

Result is displayed on the web page

# Project Structure
project-root/
│
├── app.py
├── model/
│   ├── sentiment_model.pkl
│   └── vectorizer.pkl
│
├── templates/
│   └── index.html
