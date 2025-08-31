# Overview

A Machine Learning + Flask web app that performs sentiment analysis on YouTube video comments.  
The model is trained on the Sentiment140 dataset  

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
