# Fake News Detection

This project focuses on detecting fake news using various machine learning models. It includes data preprocessing, exploratory data analysis, model training, and evaluation using cross-validation.

## Table of Contents

1. [Introduction](#introduction)
2. [About Dataset](#about-dataset)
3. [Setup Instructions](#setup-instructions)
4. [Data Preprocessing](#data-preprocessing)
5. [Exploratory Data Analysis](#exploratory-data-analysis)
6. [Model Training and Evaluation](#model-training-and-evaluation)
7. [Handling Class Balance](#handling-class-balance)
8. [Results](#results)
9. [Conclusion](#conclusion)

## Introduction

Fake news detection is an important task in today's information-rich society. This project aims to build machine learning models to classify news articles as "fake" or "real." The models used include Logistic Regression, Random Forest, and Naive Bayes. The project includes steps for data preprocessing, exploratory data analysis, and model evaluation.

## About Dataset

The dataset used for this project is specifically designed for fake news detection. It is separated into two files:

- `Fake.csv` (23,502 fake news articles)
- `True.csv` (21,417 true news articles)

Each file contains the following columns:

- **Title**: Title of the news article
- **Text**: Body text of the news article
- **Subject**: Subject of the news article
- **Date**: Publish date of the news article


## Data Preprocessing

Convert the text data into numerical features using TF-IDF vectorization and split the data into training and testing sets.

## Exploratory Data Analysis

Perform basic exploratory data analysis, including:

- **Sentiment Analysis**: Analyze the sentiment of the news articles.
- **Word Cloud**: Visualize the most common words in the dataset.
- **Class Distribution**: Check the distribution of 'fake' and 'real' news articles.

## Model Training and Evaluation

Train and evaluate multiple machine learning models, including:

- Logistic Regression
- Random Forest
- Naive Bayes

Evaluate each model using cross-validation and report metrics such as accuracy, precision, recall, and F1-score.

## Handling Class Balance

Since the dataset classes are more or less balanced, standard training procedures are followed without the need for additional techniques to address class imbalance.

## Results

The performance of the models is evaluated using cross-validation and on the test set. Metrics such as accuracy, precision, recall, and F1-score are reported, along with confusion matrices for each model.

## Conclusion

This project demonstrates the process of building and evaluating machine learning models for fake news detection. By using cross-validation and comprehensive evaluation metrics, the models achieve robust performance on the test set.
