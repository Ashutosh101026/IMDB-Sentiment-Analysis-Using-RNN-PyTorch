# IMDB Sentiment Analysis using RNN (PyTorch)

## Overview

This project performs binary sentiment classification on the IMDB Movie Reviews dataset using Natural Language Processing (NLP) and a Recurrent Neural Network (RNN) implemented in PyTorch. The workflow includes text preprocessing, TF-IDF vectorization, model training, and sentiment prediction.

---

## Dataset

- Dataset: IMDB Movie Reviews Dataset
- Reviews: 50,000
- Classes:
  - Positive
  - Negative

---

## Features

- Text preprocessing
- Data cleaning
- Label encoding
- TF-IDF vectorization
- Train-Test Split
- Custom PyTorch Dataset
- DataLoader implementation
- Recurrent Neural Network (RNN)
- Binary Sentiment Classification
- Model evaluation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- PyTorch
- Matplotlib

---

## Project Workflow

1. Load IMDB Dataset
2. Clean review text
3. Encode sentiment labels
4. Convert text into TF-IDF features
5. Split dataset into training and testing sets
6. Create PyTorch Dataset and DataLoader
7. Build an RNN model
8. Train the model using Binary Cross Entropy Loss
9. Evaluate model performance

---

## Model Architecture

Input Text

↓

TF-IDF Vectorization

↓

RNN Layer

↓

Fully Connected Layer

↓

Sigmoid Activation

↓

Positive / Negative Prediction

---

## Results

The model successfully classifies movie reviews into positive and negative sentiments using a custom RNN architecture built with PyTorch.

---

## Future Improvements

- LSTM
- GRU
- BERT
- Word2Vec embeddings
- GloVe embeddings
- Attention Mechanism
- Hyperparameter tuning
- Confusion Matrix
- ROC Curve
- F1 Score

---

## Author

Ashutosh Mehta
