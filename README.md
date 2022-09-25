# Quora-Question-Pair-Similarity
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

![image](https://user-images.githubusercontent.com/114361354/192164622-8e4de616-7987-4e3e-83b9-97625b29018f.png)

 ## Sources/Useful Links

- Source : https://www.kaggle.com/c/quora-question-pairs

- Discussions : https://www.kaggle.com/anokas/data-analysis-xgboost-starter-0-35460-lb/comments

- Kaggle Winning Solution and other approaches: https://www.dropbox.com/sh/93968nfnrzh8bp5/AACZdtsApc1QSTQc7X0H3QZ5a?dl=0

- Blog 1 : https://engineering.quora.com/Semantic-Question-Matching-with-Deep-Learning

- Blog 2 : https://towardsdatascience.com/identifying-duplicate-questions-on-quora-top-12-on-kaggle-4c1cf93f1c30
