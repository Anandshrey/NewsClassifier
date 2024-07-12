# News Classifier

## Overview
This repository contains the python code for a deep-learning-based news classifier using a Bidirectional Long Short-Term Memory (Bi-LSTM) network, a variant of Recurrent Neural Networks (RNN). The classifier will perform a Supervised multi-class classification into 4 news categories - Business/Entertainment/Medical/Technical.

## Dataset
UCI News aggregator uci-news-aggregator.csv having 422,937 news stories collected by a web aggregator between March 10th, 2014 and August 10th, 2014. 
The dataset is available on Kaggle at https://www.kaggle.com/datasets/uciml/news-aggregator-dataset

## Requirements
If running in a local environment, the following command can be used to install the required packages:

pip install -r requirements.txt


## Sections
This repository is divided into the following sections:

- Load Data and perform EDA
- One-hot Encode Categorical field
- Create Word Embeddings
- Define and train a Bidirectional LSTM model
- Analyze Model Performance
