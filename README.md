# Sentiment Analysis on IMDB Movie Reviews

## Overview

This project focuses on building a **Sentiment Analysis model** to classify movie reviews as **positive or negative** using the IMDB dataset.
The goal is to apply Natural Language Processing (NLP) techniques and Deep Learning models to understand and analyze textual sentiment from user reviews.

The project includes **data preprocessing, text vectorization, model training using LSTM, and performance evaluation**.

---

## Dataset

The dataset used in this project is the **IMDB Movie Reviews Dataset**, which contains labeled movie reviews for sentiment classification.

* Total reviews: 50,000
* Sentiment labels:

  * Positive
  * Negative

The dataset is widely used for benchmarking sentiment analysis models.

---

## Project Pipeline

### 1. Data Preprocessing

Text data was cleaned and prepared before feeding it into the model.

Steps included:

* Converting text to lowercase
* Removing HTML tags
* Removing punctuation and non-alphabetic characters
* Removing extra spaces

---

### 2. Text Tokenization

The cleaned text was converted into numerical form using **Keras Tokenizer**.

Steps included:

* Tokenizing the text
* Creating a vocabulary dictionary
* Converting text into integer sequences

---

### 3. Sequence Padding

Because neural networks require fixed-length input, sequences were padded using:

* `pad_sequences`
* Ensuring all reviews have the same length

---

### 4. Model Architecture

A **Deep Learning model using LSTM** was built to capture contextual relationships between words.

Model components include:

* **Embedding Layer** – Converts words into dense vector representations
* **LSTM Layer** – Captures sequential dependencies in text
* **Dense Layer** – Produces the final classification output

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* TensorFlow / Keras
* Natural Language Processing (NLP)

---

## Model Evaluation

The model was evaluated using several metrics:

* Accuracy
* Confusion Matrix
* Classification Report

These metrics help measure how well the model distinguishes between positive and negative reviews.

---

## Results

The trained model successfully learned patterns in the reviews and was able to classify sentiments with good accuracy.

This demonstrates how **deep learning models such as LSTM can effectively capture contextual meaning in textual data**.

---


## Future Improvements

Possible enhancements for this project include:

* Using **pretrained embeddings (Word2Vec / GloVe)**
* Trying **Bidirectional LSTM**
* Applying **Transformer-based models (BERT)**
* Performing **hyperparameter tuning**

---

## Author

Nada Kamel Abdelaal
Data Science / Machine Learning Enthusiast
