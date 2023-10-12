# Sentiment_Analysis_BERT

## Overview

This project focuses on building a sentiment analysis model using the BERT (Bidirectional Encoder Representations from Transformers) model in PyTorch. The IMDB movie review dataset is used, which contains reviews labeled as either positive or negative.

### Steps
## 1. Setup and Dependencies
- Set up a Python environment with necessary libraries including PyTorch, Transformers, pandas, and seaborn.
- Check for GPU availability to leverage accelerated training and inference.

## 2.  Data Loading and Preprocessing
- Load the IMDB movie review dataset.
- Split the dataset into training and testing sets.
- Visualize the distribution of sentiment labels in the dataset to understand the balance.

## 3.  Tokenization
- Use the BERT tokenizer from the transformers library to convert movie reviews into tokens that BERT can understand.
- Prepare data loaders for efficient feeding into the model during training and evaluation.

## 4. Model Definition
- Design a custom PyTorch model, SentimentBERT.
- The model uses the pretrained BERT model for feature extraction.
- A classification layer is added on top to predict the sentiment of reviews.

## 5. Training and Evaluation
- Train the model using a suitable loss function and optimizer.
- Evaluate the model's performance on the test dataset.
- Analyze the model's ability to predict positive and negative sentiments accurately.
