# Overview

A Machine Learning + Flask web app using TensorFlow/Keras to classify Youtube video comments as Positive, Neu-
tral, or Negative.   
The model is trained on the Sentiment140 dataset. 

# Features

- **ML Model Training (TensorFlow + Keras):**
Tokenizes and pads text sequences.  
Embedding + GlobalAveragePooling + Dense Neural Network. 
Achieves high accuracy on sentiment classification.  

- **Sentiment Prediction:**  
Loads trained model and tokenizer to predict sentiments on new text.  

- **YouTube Integration:**  
Uses YouTube Data API to fetch video comments.  

- **Web App (Flask):**
Simple frontend form to enter a YouTube video URL.  
Displays comment-wise sentiment results and a summary table.  

# Tech Stack
Python 3  
TensorFlow / Keras (ML model)  
Flask (Web framework)  
Google YouTube Data API (Fetch comments)  

# Installation

Clone this repository  
Create a virtual environment and install dependencies   
Set up Youtube API key and create a .env file in project root and add the api key there.
Download training data https://www.kaggle.com/datasets/kazanova/sentiment140?resource=download and Place it as data.csv in the project root.     

To train the model on Sentiment140 dataset:  
python training.py  

To run the app: cd app  
python server.py  
Open browser :http://127.0.0.1:5000/   

Enter a YouTube video URL to see the sentiment summary.  
