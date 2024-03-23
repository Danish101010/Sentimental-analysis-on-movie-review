# Sentiment Analysis on Movie Review Dataset

This repository contains code for sentiment analysis on a movie review dataset using a bidirectional LSTM model. The goal of this project is to classify movie reviews as either positive or negative sentiments.

## Overview

Sentiment analysis, also known as opinion mining, is a natural language processing task that involves determining the sentiment expressed in a piece of text. In this project, we apply sentiment analysis to movie reviews to classify them as positive or negative.

We utilize a bidirectional LSTM (Long Short-Term Memory) model for sentiment classification. LSTMs are a type of recurrent neural network (RNN) that are well-suited for sequence data like text due to their ability to capture long-range dependencies.

## Dataset

The movie review dataset consists of a collection of movie reviews along with their corresponding sentiment labels (positive or negative). This dataset serves as the training and evaluation data for the sentiment analysis task.

## Model Architecture

The bidirectional LSTM model architecture consists of an embedding layer, followed by multiple bidirectional LSTM layers, and finally fully connected layers for classification. Bidirectional LSTMs enable the model to capture information from both past and future time steps in the input sequence, enhancing its ability to understand the context of the text.



## Results

The trained bidirectional LSTM model achieves competitive performance on the movie review dataset, with test accuracy of 88.3 % .
