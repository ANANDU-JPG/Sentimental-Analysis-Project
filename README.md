  # Sentiment Analysis Web Application


A Flask-based web application that predicts the sentiment of user-provided text using a pre-trained machine learning model. The app cleans and vectorizes input text before classifying it as positive or negative sentiment.


 # Features

Web-based user interface for sentiment prediction

Text preprocessing (cleaning and normalization)

Pre-trained ML model integration using pickle

Fast and lightweight Flask backend

Simple and clean project structure

# How it works

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

# Clone the Repository
git clone https://github.com/your-username/sentiment-analysis-flask.git
cd sentiment-analysis-flask

# Running the Application
python app.py


The application will start at:

http://127.0.0.1:5000/
