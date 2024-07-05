# Basic-Movie-Recommendation-system

This repository contains implementations of a movie recommendation system with three machine learning models based on different recommendation criteria, using the Movielens 100k dataset.

## RNN-based Collaborative Filtering Model

### Description:
This model combines Recurrent Neural Networks (RNNs) with collaborative filtering techniques to recommend movies based on sequential user interactions.

### Features:
- Sequence Modeling for user interactions
- Memory of previous interactions through RNNs
- Utilizes collaborative filtering principles for recommendation
- Supports LSTM and GRU variants for improved performance

## Content-Based Filtering Model

### Description:
The content-based filtering model recommends movies based on similarities in movie attributes such as genre, actors, and plot summary.

### Features:
- Analysis of movie attributes to suggest similar movies
- Uses cosine similarity or Euclidean distance for similarity metrics
- Efficient handling of large datasets and diverse movie features
- Personalized recommendations based on user preferences

## Hybrid-based Model

### Description:
The hybrid model integrates collaborative filtering and content-based filtering approaches to provide personalized movie recommendations.

### Features:
- Combines strengths of collaborative filtering and content-based filtering
- Utilizes neural networks to learn complex user-item interactions
- Provides scalable solutions for diverse user preferences and large datasets
- Enhances recommendation accuracy through hybridization of recommendation techniques

## Dependencies:
- TensorFlow
- TensorFlow Datasets
- Numpy
- Pandas
- Keras

## Author
Gayathri K
