# Quora-Question-Pairs-Similarity
Machine Learning 

## Problem Statement

- dentify which questions asked on Quora are duplicates of questions that have already been asked.

- This could be useful to instantly provide answers to questions that have already been answered.

- We are tasked with predicting whether a pair of questions are duplicates or not.

## Real world/Business Objectives and Constraints  

- The cost of a mis-classification can be very high.

- You would want a probability of a pair of questions to be duplicates so that you can choose any threshold of choice.

- No strict latency concerns.

- Interpretability is partially important.

## Data Overview 
- Data will be in a file Train.csv

- Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate

- Size of Train.csv - 60MB

- Number of rows in Train.csv = 404,290

## Performance Metric 

- Source: https://www.kaggle.com/c/quora-question-pairs#evaluation

## Metric(s)

- log-loss : https://www.kaggle.com/wiki/LogarithmicLoss

- Binary Confusion Matrix

## Machine Learning Models
+---------------------+----------------+---------------+
|      Model Name     | Train Log Loss | Test Log Loss |
+---------------------+----------------+---------------+
|     Random Model    |      0.88      |     00.89     |
| Logistic Regression |      0.51      |      0.52     |
|      Linear SVM     |      0.47      |      0.48     |
|       XGBoost       |      0.35      |      0.35     |
+---------------------+----------------+---------------+

