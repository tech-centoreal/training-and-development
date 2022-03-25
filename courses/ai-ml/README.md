- [Fundamentals of ML](#fundamentals-of-ml)
  - [Introduction to AI and ML](#introduction-to-ai-and-ml)
    - [What is AI, ML?](#what-is-ai-ml)
    - [Applications of ML](#applications-of-ml)
    - [ML Components](#ml-components)
    - [Supervised Learning](#supervised-learning)
    - [Classification, Regression](#classification-regression)
    - [Python for ML](#python-for-ml)
  - [Linear Regression](#linear-regression)
    - [Hypothesis function](#hypothesis-function)
    - [Cost function](#cost-function)
    - [Gradient Descent](#gradient-descent)
    - [Normal Equation](#normal-equation)
    - [Vectorization](#vectorization)
    - [Polynomial Regression](#polynomial-regression)
  - [K-Nearest Neighbours](#k-nearest-neighbours)
    - [k-NN for Classification](#k-nn-for-classification)
    - [Choice of K](#choice-of-k)
    - [KD Trees](#kd-trees)
    - [LSH and Inverted Indices](#lsh-and-inverted-indices)
    - [Instance Based Learning](#instance-based-learning)
  - [Logistic Regression](#logistic-regression)
    - [Sigmoid function](#sigmoid-function)
    - [Cost function](#cost-function-1)
    - [Maximum Liklihood Estimate](#maximum-liklihood-estimate)
    - [GD for Logistics Regression](#gd-for-logistics-regression)
    - [Multiclass Classification](#multiclass-classification)
  - [Data preprocessing](#data-preprocessing)
    - [Handling missing values](#handling-missing-values)
    - [One-hot Encoding](#one-hot-encoding)
    - [Feature Scaling](#feature-scaling)
    - [Feature Selection](#feature-selection)
  - [Regularization](#regularization)
    - [Overfitting](#overfitting)
    - [Underfitting](#underfitting)
    - [Regularized Linear Regression](#regularized-linear-regression)
    - [Regularized Logistic Regression](#regularized-logistic-regression)
- [Supervised Machine Learning Algorithms](#supervised-machine-learning-algorithms)
  - [SVM](#svm)
    - [Maximum Margin Classifier](#maximum-margin-classifier)
    - [Support Vectors](#support-vectors)
    - [Handling Outliers](#handling-outliers)
    - [Kernels](#kernels)
    - [SVM as Large Margin Classifier](#svm-as-large-margin-classifier)
    - [Constrained Optimization](#constrained-optimization)
  - [Decision Trees](#decision-trees)
    - [Choosing the best attribute](#choosing-the-best-attribute)
      - [Entropy](#entropy)
      - [Information Gain](#information-gain)
    - [Gini Index](#gini-index)
    - [ID3, C4.5](#id3-c45)
    - [Handling missing values](#handling-missing-values-1)
    - [Pruning](#pruning)
      - [Reduced-error pruning](#reduced-error-pruning)
      - [Rule post-pruning](#rule-post-pruning)
    - [Limitations of Decision Trees](#limitations-of-decision-trees)
  - [Naive Bayes](#naive-bayes)
    - [Conditional Probability & Bayes Rule](#conditional-probability--bayes-rule)
    - [Naive Bayes Classifier](#naive-bayes-classifier)
    - [Naive Bayes Algorithm](#naive-bayes-algorithm)
    - [Laplace Smoothing](#laplace-smoothing)
    - [NB for Text Classification](#nb-for-text-classification)
    - [Handling Real-world problems](#handling-real-world-problems)
  - [Algorithms for Regression](#algorithms-for-regression)
    - [Regression Trees](#regression-trees)
      - [Choice of Threshold & Attribute](#choice-of-threshold--attribute)
      - [Overfitting](#overfitting-1)
      - [Cost Complexity Pruning](#cost-complexity-pruning)
    - [k-NN for Regression](#k-nn-for-regression)
    - [Locally Weighted Regression](#locally-weighted-regression)
  - [Learning Theory](#learning-theory)
    - [Evaluation of Hypothesis function](#evaluation-of-hypothesis-function)
    - [Tuning Hyperparameters](#tuning-hyperparameters)
    - [Bias, Variance and Noise Decomposition](#bias-variance-and-noise-decomposition)
    - [Error Analysis](#error-analysis)
    - [Performance Optimization](#performance-optimization)
  - [Bagging](#bagging)
    - [Bootstrapping](#bootstrapping)
    - [Out-of-Bag error](#out-of-bag-error)
    - [Bagged Decision Trees](#bagged-decision-trees)
    - [Random Forests](#random-forests)
  - [Boosting](#boosting)
    - [Gradient Boosting](#gradient-boosting)
    - [AdaBoost](#adaboost)
    - [Stochastic Gradient Boosting](#stochastic-gradient-boosting)
    - [ECOC](#ecoc)
    - [Stacking](#stacking)
- [Competitive Machine Learning](#competitive-machine-learning)
  - [Introduction](#introduction)
    - [Introduction to Competitive ML](#introduction-to-competitive-ml)
    - [Exploratory Data Analysis](#exploratory-data-analysis)
      - [Introduction to Pandas](#introduction-to-pandas)
      - [Visualizations](#visualizations)
      - [Dataset Cleaning](#dataset-cleaning)
    - [Introduction to scikit-learn](#introduction-to-scikit-learn)
  - [Advanced Pre-processing & Feature Engineering](#advanced-pre-processing--feature-engineering)
    - [Review of previously covered techniques](#review-of-previously-covered-techniques)
    - [Missing Values Imputation](#missing-values-imputation)
    - [Label Encoding](#label-encoding)
    - [Target Encoding](#target-encoding)
    - [Mean Target Encoding](#mean-target-encoding)
    - [Feature Interactions](#feature-interactions)
  - [Validation](#validation)
    - [k-fold Cross Validation](#k-fold-cross-validation)
    - [Validation Strategies](#validation-strategies)
    - [Data-splitting Strategies](#data-splitting-strategies)
    - [Pros and Cons of Validation](#pros-and-cons-of-validation)
  - [Modelling](#modelling)
    - [Recap of ML Aglorithms](#recap-of-ml-aglorithms)
    - [Hyperparameter Tuning](#hyperparameter-tuning)
    - [Grid Search](#grid-search)
    - [Advanced Model Ensembling](#advanced-model-ensembling)
    - [Recap of Metrics](#recap-of-metrics)
    - [Metrics Optimization](#metrics-optimization)
- [Introduction to Deep Learning](#introduction-to-deep-learning)
  - [Introduction to Neural Networks](#introduction-to-neural-networks)
    - [Understandig how the Brain works](#understandig-how-the-brain-works)
    - [Model representation](#model-representation)
    - [Vectorizing](#vectorizing)
    - [Activation Functions](#activation-functions)
  - [Backpropagation](#backpropagation)
    - [Intution and the Algorithm](#intution-and-the-algorithm)
    - [Gradient Checking](#gradient-checking)
    - [Initialization](#initialization)
  - [Introduction to TensorFlow](#introduction-to-tensorflow)
    - ["Hello World" from Neural networks](#hello-world-from-neural-networks)
    - [Loading Training Data](#loading-training-data)
    - [Coding Compute Vision NN](#coding-compute-vision-nn)
    - [Using callbacks](#using-callbacks)
  - [Deep Neural Networks](#deep-neural-networks)
    - [Forward propagation](#forward-propagation)
    - [Building blocks](#building-blocks)
    - [Forward and Backward propagation](#forward-and-backward-propagation)
    - [Hyperparameters](#hyperparameters)
  - [Practical Considerations for Applying Neural Networks](#practical-considerations-for-applying-neural-networks)
    - [Normalizing Inputs](#normalizing-inputs)
    - [Bias, Variance](#bias-variance)
    - [Initialization](#initialization-1)
    - [Regularization](#regularization-1)
    - [Dropouts](#dropouts)
    - [Gradient Checking](#gradient-checking-1)
  - [Hyperparameter Tuning](#hyperparameter-tuning-1)
    - [Using appropriate scale](#using-appropriate-scale)
    - [Normalizing Activations](#normalizing-activations)
    - [Batch Normalization](#batch-normalization)
    - [Softmax Regression](#softmax-regression)
  - [Optimization](#optimization)
    - [Mini-batch gradient descent](#mini-batch-gradient-descent)
    - [Exponentially weighted averages](#exponentially-weighted-averages)
    - [Gradient descent with momentum](#gradient-descent-with-momentum)
    - [RMSprop](#rmsprop)
    - [Learning rate decay](#learning-rate-decay)
  - [Practical Advice for applying Deep Learning](#practical-advice-for-applying-deep-learning)
    - [Orthogonalization](#orthogonalization)
    - [Working with Train/Test datasets](#working-with-traintest-datasets)
    - [Setting proper evaluation metrics](#setting-proper-evaluation-metrics)
    - [Data augmentation](#data-augmentation)
    - [Improving model performance](#improving-model-performance)
    - [Error analysis](#error-analysis-1)
    - [Working with different data](#working-with-different-data)
    - [Cleaning bad data](#cleaning-bad-data)
    - [Transfer learning](#transfer-learning)
    - [Multi-task learning](#multi-task-learning)
  - [ML Engineering](#ml-engineering)
    - [Dynamic Training and Inference](#dynamic-training-and-inference)
    - [Fairness](#fairness)
    - [Data dependencies](#data-dependencies)
- [CNNs and Computer Vision](#cnns-and-computer-vision)
  - [CNN Basics](#cnn-basics)
    - [Edge Detection](#edge-detection)
    - [Strided Convolutions](#strided-convolutions)
    - [Convolutions over volume](#convolutions-over-volume)
    - [Pooling Layers](#pooling-layers)
  - [Deep CNNs](#deep-cnns)
    - [ResNets](#resnets)
    - [Inception Network](#inception-network)
    - [Transfer Learning](#transfer-learning-1)
    - [Computer Vision](#computer-vision)
    - [Object Detection](#object-detection)
    - [Face Recognition](#face-recognition)
  - [Intro to CNNs in TensorFlow](#intro-to-cnns-in-tensorflow)
    - [Implementing Convolutional layers](#implementing-convolutional-layers)
    - [Implementing pooling layers](#implementing-pooling-layers)
    - [Waling through CNN of real-world images (dev, training)](#waling-through-cnn-of-real-world-images-dev-training)
    - [Testing Accuracy](#testing-accuracy)
  - [Advanced CNN in TensorFlow](#advanced-cnn-in-tensorflow)
    - [Working with Larger Datasets](#working-with-larger-datasets)
    - [Avoiding overfittig with](#avoiding-overfittig-with)
    - [Transfer Learning](#transfer-learning-2)
    - [Multi-class Classifications](#multi-class-classifications)
- [RNNs and Natural Language Processing](#rnns-and-natural-language-processing)
  - [Intro to RNNs](#intro-to-rnns)
    - [Sequence Models](#sequence-models)
    - [Backpropagation through time](#backpropagation-through-time)
    - [Sampling](#sampling)
    - [GRU](#gru)
    - [LSTM](#lstm)
    - [Bidirectional RNNs](#bidirectional-rnns)
  - [Natural Language Processing](#natural-language-processing)
    - [Word Representation](#word-representation)
    - [Word Embeddings](#word-embeddings)
    - [Word2Vec](#word2vec)
    - [GloVe vectors](#glove-vectors)
    - [Sentiment classification](#sentiment-classification)
  - [Speech Recognition](#speech-recognition)
    - [Beam Search](#beam-search)
    - [Bleu Score](#bleu-score)
    - [Attention Model](#attention-model)
    - [Trigger Word Detection](#trigger-word-detection)
  - [NLP in TensorFlow](#nlp-in-tensorflow)
    - [Word-based encodings](#word-based-encodings)
    - [Tokenizer](#tokenizer)
    - [Word embeddings with IMDb dataset](#word-embeddings-with-imdb-dataset)
    - [Implementing LSTMs](#implementing-lstms)
    - [Working with Sequence Models](#working-with-sequence-models)
  - [Advanced RNNs in TensorFlow](#advanced-rnns-in-tensorflow)
    - [Working with Time series problems](#working-with-time-series-problems)
    - [Forecasting problem](#forecasting-problem)
    - [Lambda layers](#lambda-layers)
    - [Dynamically adjusting learing rates](#dynamically-adjusting-learing-rates)
    - [Using Bi-directional LSTMs on real-world time series data](#using-bi-directional-lstms-on-real-world-time-series-data)
- [Unsupervised Learning Algorithms](#unsupervised-learning-algorithms)
  - [Clustering](#clustering)
    - [Introduction to Unsupervised Learning](#introduction-to-unsupervised-learning)
    - [K-Means clustering](#k-means-clustering)
    - [Hierarchical clustering](#hierarchical-clustering)
    - [Density based clustering](#density-based-clustering)
    - [Gaussian Mixture models](#gaussian-mixture-models)
  - [Dimentionality Reduction Techniques](#dimentionality-reduction-techniques)
    - [Principal Component Analysis (PCA)](#principal-component-analysis-pca)
    - [Independent Component Analysis (ICA)](#independent-component-analysis-ica)
    - [PCA vs ICA](#pca-vs-ica)
    - [Singular Value Decomposition (SVD)](#singular-value-decomposition-svd)
    - [Non-negative Matrix Factorization](#non-negative-matrix-factorization)
  - [Semi-Supervised Learning](#semi-supervised-learning)
    - [Introduction to Semi-Supervised Learning](#introduction-to-semi-supervised-learning)
    - [Self Training](#self-training)
    - [Generative Models](#generative-models)
      - [Mixture of Gaussian Distributions (GMM)](#mixture-of-gaussian-distributions-gmm)
      - [Mixture of Multinomial Distributions](#mixture-of-multinomial-distributions)
      - [Hidden Marcov Models (HMM)](#hidden-marcov-models-hmm)
    - [Graph-Based Algorithms](#graph-based-algorithms)
      - [Minicut](#minicut)
      - [Harmonic](#harmonic)
      - [Local and Global consistency](#local-and-global-consistency)
      - [Manifold Regularization](#manifold-regularization)
- [Search Based AI](#search-based-ai)
  - [Uninformed Search](#uninformed-search)
    - [Breadth-first search](#breadth-first-search)
    - [Depth-first search](#depth-first-search)
    - [Depth Limited Search](#depth-limited-search)
    - [Iterative Deepening Search](#iterative-deepening-search)
    - [Uniform Cost Search](#uniform-cost-search)
    - [Bidirectional Search](#bidirectional-search)
  - [Informed Search](#informed-search)
    - [Heuristic evaluation function](#heuristic-evaluation-function)
    - [Greedy Best-First Search](#greedy-best-first-search)
    - [A* Search](#a-search)
    - [Memory Bounded Search](#memory-bounded-search)
    - [Iterative Deepening A* Memory Bounded Search](#iterative-deepening-a-memory-bounded-search)
    - [RBFS](#rbfs)
  - [Non-classic Search](#non-classic-search)
    - [Hill-climbing Search](#hill-climbing-search)
    - [Local Beam Search](#local-beam-search)
    - [Simulated Annealing](#simulated-annealing)
    - [Search in non-deterministic actions](#search-in-non-deterministic-actions)
    - [Search with partial obervations](#search-with-partial-obervations)
  - [Adversarial Search](#adversarial-search)
    - [Minimax Algorithm](#minimax-algorithm)
    - [Alpha-Beta Pruning](#alpha-beta-pruning)
    - [AI for Stochastic Games](#ai-for-stochastic-games)
    - [AI for Partially observable Games](#ai-for-partially-observable-games)
- [Reinforcement Learning](#reinforcement-learning)
  - [Markov Decision Process](#markov-decision-process)
    - [Agent and Environment Interfaces](#agent-and-environment-interfaces)
    - [Goals & Rewards](#goals--rewards)
    - [Markov Decision Processes](#markov-decision-processes)
    - [Value functions](#value-functions)
    - [Optimal Value functions](#optimal-value-functions)
  - [Planning Algorithms](#planning-algorithms)
    - [Bellman equations](#bellman-equations)
    - [Dynamic Programming](#dynamic-programming)
    - [Policy Evaluation](#policy-evaluation)
    - [Policy Improvement](#policy-improvement)
    - [Policy Iteration](#policy-iteration)
    - [Value Iteration](#value-iteration)
  - [Monte Carlo methods](#monte-carlo-methods)
    - [Monte Carlo Prediction](#monte-carlo-prediction)
    - [Monte Carlo Estimation of Action Values](#monte-carlo-estimation-of-action-values)
    - [Monte Carlo Control](#monte-carlo-control)
    - [Off-policy Prediction](#off-policy-prediction)
    - [Off-policy Monte Carlo Control](#off-policy-monte-carlo-control)
  - [Temporal Difference Learning](#temporal-difference-learning)
    - [TD(O) Algorithm](#tdo-algorithm)
    - [TD (λ) Algorithm](#td-λ-algorithm)
    - [Q-learning Algorithm](#q-learning-algorithm)
    - [SARSA](#sarsa)
    - [Games](#games)
  - [Value-Based methods](#value-based-methods)
    - [Deep Q-Learning Network (DQN)](#deep-q-learning-network-dqn)
    - [Double DQN](#double-dqn)
    - [Noisy DQN](#noisy-dqn)
    - [Prioritized Replay](#prioritized-replay)
    - [Deep Reinforcement Learning for Robotics](#deep-reinforcement-learning-for-robotics)
  - [Policy-Gradient Methods](#policy-gradient-methods)
    - [Policy-Gradient Theorem](#policy-gradient-theorem)
    - [REINFORCE](#reinforce)
    - [Generalized Advantage Estimation (GAE)](#generalized-advantage-estimation-gae)
    - [Natual Policy Gradient (NPG)](#natual-policy-gradient-npg)
    - [Trust-Region Policy Optimization (TRPO)](#trust-region-policy-optimization-trpo)
    - [Proximal Policy Optimization (PPO)](#proximal-policy-optimization-ppo)
- [Recommendation Systems](#recommendation-systems)
  - [Introduction to Recommendation Systems](#introduction-to-recommendation-systems)
    - [Definitions](#definitions)
    - [Applications of recommendation systems](#applications-of-recommendation-systems)
    - [Real-world use cases](#real-world-use-cases)
    - [Types of recommendation systems](#types-of-recommendation-systems)
  - [Content-based Recommendation systems](#content-based-recommendation-systems)
    - [Components of content-based systems](#components-of-content-based-systems)
    - [Preprocessing and Feature Engineering](#preprocessing-and-feature-engineering)
    - [Bayes Classifiers](#bayes-classifiers)
    - [Rule-based Classifiers](#rule-based-classifiers)
    - [Regression-based Models](#regression-based-models)
  - [Collaborative Filtering recommendation systems](#collaborative-filtering-recommendation-systems)
    - [Types of user feedback data](#types-of-user-feedback-data)
    - [Decision and Regression Trees](#decision-and-regression-trees)
    - [Matrix Factorization Methods](#matrix-factorization-methods)
      - [ALS Algorithm](#als-algorithm)
      - [Principal Component Analysis (PCA)](#principal-component-analysis-pca-1)
      - [Singular Factor Decomposition (SFD)](#singular-factor-decomposition-sfd)
    - [Rule-based collaborative filtering](#rule-based-collaborative-filtering)
    - [Naive Bayes collaborative filtering](#naive-bayes-collaborative-filtering)
  - [Neighbourhood-based collaborative filtering](#neighbourhood-based-collaborative-filtering)
    - [Similarity Metrix](#similarity-metrix)
    - [User-based collaborative filtering](#user-based-collaborative-filtering)
    - [Item-based collaborative filtering](#item-based-collaborative-filtering)
    - [Combination of techniques](#combination-of-techniques)
  - [Other Recommendation Systems](#other-recommendation-systems)
    - [Context-based](#context-based)
    - [Location sensitive](#location-sensitive)
    - [Time-based](#time-based)
    - [Hybrid and Ensemble](#hybrid-and-ensemble)
  - [Deep Learning for Recommendation Systems](#deep-learning-for-recommendation-systems)
    - [Context-Aware algorithms](#context-aware-algorithms)
    - [Restricted-Boltzman Machines (RBM)](#restricted-boltzman-machines-rbm)
      - [Introduction](#introduction-1)
      - [Evaluating the RBM recommender](#evaluating-the-rbm-recommender)
    - [Modelling using Context-Aware algorithms](#modelling-using-context-aware-algorithms)
    - [Clickstream recommendations with RNN's](#clickstream-recommendations-with-rnns)
  - [Evaluation of Recommendation Systems](#evaluation-of-recommendation-systems)
    - [Valiation](#valiation)
    - [Evaluation Metrics](#evaluation-metrics)
    - [Evaluation Design](#evaluation-design)
    - [Accuracy and Coverage](#accuracy-and-coverage)
    - [Novelty and Diversity](#novelty-and-diversity)
    - [Robustness, Stability and Scalability](#robustness-stability-and-scalability)
    - [Limitations of recommender systems](#limitations-of-recommender-systems)

# Fundamentals of ML

## Introduction to AI and ML

### What is AI, ML?

### Applications of ML

### ML Components

### Supervised Learning

### Classification, Regression

### Python for ML

## Linear Regression

### Hypothesis function

### Cost function

### Gradient Descent

### Normal Equation

### Vectorization

### Polynomial Regression

## K-Nearest Neighbours

### k-NN for Classification

### Choice of K

### KD Trees

### LSH and Inverted Indices

### Instance Based Learning

## Logistic Regression

### Sigmoid function

### Cost function

### Maximum Liklihood Estimate

### GD for Logistics Regression

### Multiclass Classification

## Data preprocessing

### Handling missing values

### One-hot Encoding

### Feature Scaling

### Feature Selection

## Regularization

### Overfitting

### Underfitting

### Regularized Linear Regression

### Regularized Logistic Regression

# Supervised Machine Learning Algorithms

## SVM

### Maximum Margin Classifier

### Support Vectors

### Handling Outliers

### Kernels

### SVM as Large Margin Classifier

### Constrained Optimization

## Decision Trees

### Choosing the best attribute

#### Entropy

#### Information Gain

### Gini Index

### ID3, C4.5

### Handling missing values

### Pruning

#### Reduced-error pruning

#### Rule post-pruning

### Limitations of Decision Trees

## Naive Bayes

### Conditional Probability & Bayes Rule

### Naive Bayes Classifier

### Naive Bayes Algorithm

### Laplace Smoothing

### NB for Text Classification

### Handling Real-world problems

## Algorithms for Regression

### Regression Trees

#### Choice of Threshold & Attribute

#### Overfitting

#### Cost Complexity Pruning

### k-NN for Regression

### Locally Weighted Regression

## Learning Theory

### Evaluation of Hypothesis function

### Tuning Hyperparameters

### Bias, Variance and Noise Decomposition

### Error Analysis

### Performance Optimization

## Bagging

### Bootstrapping

### Out-of-Bag error

### Bagged Decision Trees

### Random Forests

## Boosting

### Gradient Boosting

### AdaBoost

### Stochastic Gradient Boosting

### ECOC

### Stacking

# Competitive Machine Learning

## Introduction

### Introduction to Competitive ML

### Exploratory Data Analysis

#### Introduction to Pandas

#### Visualizations

#### Dataset Cleaning

### Introduction to scikit-learn

## Advanced Pre-processing & Feature Engineering

### Review of previously covered techniques

### Missing Values Imputation

### Label Encoding

### Target Encoding

### Mean Target Encoding

### Feature Interactions

## Validation

### k-fold Cross Validation

### Validation Strategies

### Data-splitting Strategies

### Pros and Cons of Validation

## Modelling

### Recap of ML Aglorithms

### Hyperparameter Tuning

### Grid Search

### Advanced Model Ensembling

### Recap of Metrics

### Metrics Optimization

# Introduction to Deep Learning

## Introduction to Neural Networks

### Understandig how the Brain works

### Model representation

### Vectorizing

### Activation Functions

## Backpropagation

### Intution and the Algorithm

### Gradient Checking

### Initialization

## Introduction to TensorFlow

### "Hello World" from Neural networks

### Loading Training Data

### Coding Compute Vision NN

### Using callbacks

## Deep Neural Networks

### Forward propagation

### Building blocks

### Forward and Backward propagation

### Hyperparameters

## Practical Considerations for Applying Neural Networks

### Normalizing Inputs

### Bias, Variance

### Initialization

### Regularization

### Dropouts

### Gradient Checking

## Hyperparameter Tuning

### Using appropriate scale

### Normalizing Activations

### Batch Normalization

### Softmax Regression

## Optimization

### Mini-batch gradient descent

### Exponentially weighted averages

### Gradient descent with momentum

### RMSprop

### Learning rate decay

## Practical Advice for applying Deep Learning

### Orthogonalization

### Working with Train/Test datasets

### Setting proper evaluation metrics

### Data augmentation

### Improving model performance

### Error analysis

### Working with different data

### Cleaning bad data

### Transfer learning

### Multi-task learning

## ML Engineering

### Dynamic Training and Inference

### Fairness

### Data dependencies

# CNNs and Computer Vision

## CNN Basics

### Edge Detection

### Strided Convolutions

### Convolutions over volume

### Pooling Layers

## Deep CNNs

### ResNets

### Inception Network

### Transfer Learning

### Computer Vision

### Object Detection

### Face Recognition

## Intro to CNNs in TensorFlow

### Implementing Convolutional layers

### Implementing pooling layers

### Waling through CNN of real-world images (dev, training)

### Testing Accuracy

## Advanced CNN in TensorFlow

### Working with Larger Datasets

### Avoiding overfittig with

### Transfer Learning

### Multi-class Classifications

# RNNs and Natural Language Processing

## Intro to RNNs

### Sequence Models

### Backpropagation through time

### Sampling

### GRU

### LSTM

### Bidirectional RNNs

## Natural Language Processing

### Word Representation

### Word Embeddings

### Word2Vec

### GloVe vectors

### Sentiment classification

## Speech Recognition

### Beam Search

### Bleu Score

### Attention Model

### Trigger Word Detection

## NLP in TensorFlow

### Word-based encodings

### Tokenizer

### Word embeddings with IMDb dataset

### Implementing LSTMs

### Working with Sequence Models

## Advanced RNNs in TensorFlow

### Working with Time series problems

### Forecasting problem

### Lambda layers

### Dynamically adjusting learing rates

### Using Bi-directional LSTMs on real-world time series data

# Unsupervised Learning Algorithms

## Clustering

### Introduction to Unsupervised Learning

### K-Means clustering

### Hierarchical clustering

### Density based clustering

### Gaussian Mixture models

## Dimentionality Reduction Techniques

### Principal Component Analysis (PCA)

### Independent Component Analysis (ICA)

### PCA vs ICA

### Singular Value Decomposition (SVD)

### Non-negative Matrix Factorization

## Semi-Supervised Learning

### Introduction to Semi-Supervised Learning

### Self Training

### Generative Models

#### Mixture of Gaussian Distributions (GMM)

#### Mixture of Multinomial Distributions

#### Hidden Marcov Models (HMM)

### Graph-Based Algorithms

#### Minicut

#### Harmonic

#### Local and Global consistency

#### Manifold Regularization

# Search Based AI

## Uninformed Search

### Breadth-first search

### Depth-first search

### Depth Limited Search

### Iterative Deepening Search

### Uniform Cost Search

### Bidirectional Search

## Informed Search

### Heuristic evaluation function

### Greedy Best-First Search

### A* Search

### Memory Bounded Search

### Iterative Deepening A* Memory Bounded Search

### RBFS

## Non-classic Search

### Hill-climbing Search

### Local Beam Search

### Simulated Annealing

### Search in non-deterministic actions

### Search with partial obervations

## Adversarial Search

### Minimax Algorithm

### Alpha-Beta Pruning

### AI for Stochastic Games

### AI for Partially observable Games

# Reinforcement Learning

## Markov Decision Process

### Agent and Environment Interfaces

### Goals & Rewards

### Markov Decision Processes

### Value functions

### Optimal Value functions

## Planning Algorithms

### Bellman equations

### Dynamic Programming

### Policy Evaluation

### Policy Improvement

### Policy Iteration

### Value Iteration

## Monte Carlo methods

### Monte Carlo Prediction

### Monte Carlo Estimation of Action Values

### Monte Carlo Control

### Off-policy Prediction

### Off-policy Monte Carlo Control

## Temporal Difference Learning

### TD(O) Algorithm

### TD (λ) Algorithm

### Q-learning Algorithm

### SARSA

### Games

## Value-Based methods

### Deep Q-Learning Network (DQN)

### Double DQN

### Noisy DQN

### Prioritized Replay

### Deep Reinforcement Learning for Robotics

## Policy-Gradient Methods

### Policy-Gradient Theorem

### REINFORCE

### Generalized Advantage Estimation (GAE)

### Natual Policy Gradient (NPG)

### Trust-Region Policy Optimization (TRPO)

### Proximal Policy Optimization (PPO)

# Recommendation Systems

## Introduction to Recommendation Systems

### Definitions

### Applications of recommendation systems

### Real-world use cases

### Types of recommendation systems

## Content-based Recommendation systems

### Components of content-based systems

### Preprocessing and Feature Engineering

### Bayes Classifiers

### Rule-based Classifiers

### Regression-based Models

## Collaborative Filtering recommendation systems

### Types of user feedback data

### Decision and Regression Trees

### Matrix Factorization Methods

#### ALS Algorithm

#### Principal Component Analysis (PCA)

#### Singular Factor Decomposition (SFD)

### Rule-based collaborative filtering

### Naive Bayes collaborative filtering

## Neighbourhood-based collaborative filtering

### Similarity Metrix

### User-based collaborative filtering

### Item-based collaborative filtering

### Combination of techniques

## Other Recommendation Systems

### Context-based

### Location sensitive

### Time-based

### Hybrid and Ensemble

## Deep Learning for Recommendation Systems

### Context-Aware algorithms

### Restricted-Boltzman Machines (RBM)

#### Introduction

#### Evaluating the RBM recommender

### Modelling using Context-Aware algorithms

### Clickstream recommendations with RNN's

## Evaluation of Recommendation Systems

### Valiation

### Evaluation Metrics

### Evaluation Design

### Accuracy and Coverage

### Novelty and Diversity

### Robustness, Stability and Scalability

### Limitations of recommender systems
