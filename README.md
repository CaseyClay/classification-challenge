# classification-challenge - Spam Detector

## Overview

This project involves creating two classification models, a logistic regression model and a random forest model, to detect spam emails. The goal is to improve the email filtering system for an Internet Service Provider (ISP).

## Data Source

The dataset used for this challenge can be found here.

## Files

- `spam_detector.ipynb`: Jupyter notebook containing the challenge code.

## Instructions

The challenge consists of the following steps:

- Split the data into training and testing sets.
- Scale the features.
- Create and evaluate both logistic regression and random forest models.

## Results

The models were evaluated based on their accuracy scores. The model that performed better was Random Forest Classifer.

## Predictions

Prior to building the models, a prediction was made regarding which model would perform better. The actual results were [insert comparison with prediction].

## Requirements

The challenge was completed by fulfilling the following requirements:

- Data split into training and testing sets.
- Features scaled using StandardScaler.
- Logistic regression and random forest models created and evaluated.

## Evaluation

- Logistic Regression Model Accuracy: training:92.9%, testing: 92.6%
- Random Forest Model Accuracy: training: 99.96%, testing: 95.9%

## Conclusion

The random forest classifier model achieves a higher accuracy score (approximately 96%) compared to the logistic regression model (around 93%). This result aligns with my initial prediction that the random forest classifier would be more suitable for this use case. The dataset contains a large number of features, and random forest classifiers tend to handle non-linear relationships between features better than logistic regression models, which assume a linear relationship between features and the target outcome.
