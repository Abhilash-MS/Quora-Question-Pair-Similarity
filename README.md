# Quora-Question-Pairs-Similarity
Machine Learning 

## Problem Statement :

i) dentify which questions asked on Quora are duplicates of questions that have already been asked.

ii) This could be useful to instantly provide answers to questions that have already been answered.

iii) We are tasked with predicting whether a pair of questions are duplicates or not.

## Real world/Business Objectives and Constraints : 

i)The cost of a mis-classification can be very high.

ii)You would want a probability of a pair of questions to be duplicates so that you can choose any threshold of choice.

iii)No strict latency concerns.

iv)Interpretability is partially important.

## Data Overview 
- Data will be in a file Train.csv

- Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate

- Size of Train.csv - 60MB

- Number of rows in Train.csv = 404,290

