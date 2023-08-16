# sentiment-analysis-using-lstm
# Sentiment Analysis using LSTM

## Overview:
In this assignment, you will implement a neural network for sentiment analysis on movie reviews, classifying them as positive or negative.

## Components:

### Before you begin:
Before starting the assignment, upload the "reviews.csv" file containing movie reviews to your Google Drive. You can download the dataset from this [Dataset Link](https://drive.google.com/file/d/1nqmfdx7dj5qgynVwzD1CMjFFZoBeKrmD/view?usp=sharing) and upload it to your Drive.

### Mounting Google Drive:
Use the provided code to mount your Google Drive to access the dataset in this Colab notebook.

### Import Libraries:
Import necessary libraries including NumPy, Pandas, Matplotlib, and PyTorch for building the sentiment analysis model.

### Loading the Dataset:
Load the movie reviews dataset from your Google Drive and split it into training and testing sets.

### Preprocessing:
Preprocess the text data by converting to lowercase, removing punctuation, lemmatizing words, and removing stop words.

### Building the Vocabulary:
Create a vocabulary dictionary where each unique word is assigned a unique integer ID.

### Converting to Numerical Form:
Convert the preprocessed reviews into their numerical form using the vocabulary.

### Normalizing Review Lengths:
Normalize review lengths using padding to ensure consistent input dimensions.

### Converting to Tensors:
Convert the normalized data into PyTorch tensors using DataLoader for efficient batch loading.

### Building the Model:
Define a recurrent neural network (RNN) model using PyTorch's LSTM layer and other components.

### Training the Model:
Train the RNN model on the training data using binary cross-entropy loss and Adam optimizer.

### Visualization:
Visualize training and testing accuracy as well as loss using plots.

This assignment guides you through implementing sentiment analysis using an LSTM model to classify movie reviews as positive or negative.
