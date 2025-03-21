# IMDB Sentiment Analysis

## Overview
This project implements sentiment analysis on the IMDB dataset, which contains 50,000 movie reviews. The dataset is divided into 25,000 training and 25,000 testing samples for binary sentiment classification (positive or negative).

The model is built using two key techniques:
1. **Continuous Bag of Words (CBOW)**: Used for word embeddings.
2. **LSTM with Attention Mechanism**: Used to capture long-term dependencies in text and improve classification accuracy.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/IMDB_Logo_2016.svg/640px-IMDB_Logo_2016.svg.png">

---

## Dataset
The IMDB dataset contains highly polarized movie reviews. The goal is to classify the reviews as either **positive** or **negative** based on their sentiment.

---

## Dependencies
Ensure you have the following dependencies installed before running the project:

```bash
pip install pandas nltk tensorflow gensim scikit-learn
