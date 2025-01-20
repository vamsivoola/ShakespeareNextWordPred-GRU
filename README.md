# Shakespeare Next Word Predictor

A deep learning model that predicts the next word in a sequence based on Shakespeare's Hamlet, using GRU (Gated Recurrent Unit) neural networks.

## Overview

This project implements a next word prediction model trained on Shakespeare's Hamlet. It uses a GRU-based neural network architecture to learn the patterns and structure of Shakespearean language and predict the next word given a sequence of input words.

## Features

- Text preprocessing and tokenization
- GRU-based neural network model
- Interactive Streamlit web interface
- Pre-trained model on Shakespeare's Hamlet
- Next word prediction functionality

## Installation

1. Clone the repository:
bash
git clone https://github.com/yourusername/shakespeare-next-word-predictor.git
cd shakespeare-next-word-predictor

2. Install the required dependencies:
bash
pip install -r requirements.txt

## Project Structure

shakespeare-next-word-predictor/
├── app.py # Streamlit web application
├── training.ipynb # Model training notebook
├── requirements.txt # Project dependencies
├── shakespeare.txt # Training data
├── next_word_GRU.h5 # Trained model
└── tokenizer.pickle # Saved tokenizer

## Usage

1. Run the Streamlit application: streamlit run app.py
2. Enter a sequence of words in the input field
3. Click "Predict Next Word" to see the model's prediction
   
## Model Architecture

The model uses the following architecture:
- Embedding layer (32 dimensions)
- GRU layer (150 units) with L2 regularization
- Dropout layer (0.2)
- GRU layer (100 units) with L2 regularization
- Dense output layer with softmax activation

## Acknowledgments
- Shakespeare's Hamlet text from NLTK's Gutenberg corpus
- Inspired by natural language processing techniques in deep learning
- Kirsh Naik's Udemy Course

   







