# Fake-News-Detection
Uses LSTM networks to identify fake news. Preprocesses text, trains model, and ensures accurate classification.

This repository contains code to classify news articles into fake and real categories using Long Short-Term Memory (LSTM) neural networks. The code processes text data, preprocesses it, builds an LSTM model, trains the model, and evaluates its performance.

## Overview

- **Data Loading and Cleaning:** The code loads fake and real news data from 'Fake.csv' and 'True.csv', cleans the data, and prepares it for training.
- **Data Visualization:** Bar charts are used to visualize the distribution of fake and real news articles.
- **Text Preprocessing:** Text data is normalized, tokenized, and padded for model input.
- **Model Architecture:** The model consists of embedding layers, bidirectional LSTM layers, dense layers, and dropout layers.
- **Training and Validation:** The model is compiled, trained, and validated with early stopping to prevent overfitting.
- **Evaluation:** The trained model is evaluated on the test data, and accuracy, precision, recall scores, and confusion matrix are generated.

## Usage

1. Ensure you have the 'Fake.csv' and 'True.csv' files in the correct directory.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Run the `fake_real_news_classification.py` script to execute the code.

## Dependencies

- Pandas
- Matplotlib
- Numpy
- TensorFlow
- Scikit-learn
- Seaborn

## Results

The model's performance metrics on the test data are as follows:
- Accuracy: 99.04%
- Precision: 98.79%
- Recall: 99.20%

The confusion matrix visualizes the model's predictions on the test data.


## The dataset is from Kaggle ( https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset ).
