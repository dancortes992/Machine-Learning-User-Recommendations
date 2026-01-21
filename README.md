# Machine-Learning-User-Recommendations
### Background

This project is part of the Tripleten data science practium. Focuses of the project is machine learning classification.

## Project Description

This project encompasses an analysis of preprocessed data concerning Megaline client data and thier current subscription plans.
The purpose of this analysis is to build a predictive model capable of reliably recommending subscription plans to users based on their monthly data.
The data will be used to train diverse models using _sklearn_ library. The threshold accuracy for this project is 0.75.

## Data

Features available in our data consist of:
- сalls — number of calls,
- minutes — total call duration in minutes,
- messages — number of text messages,
- mb_used — Internet traffic used in MB,
- is_ultra — plan for the current month (Ultra - 1, Smart - 0).

**Train data split ratio:** 3:1:1

**Models evaluated:** DecisionTreeClassifier, RandomForestClassifier, LogisticRegression

## Findings

Results on both validation and primarly test sets demonstrate both decision tree and random forest algorithms to produce the highest accuracy score, thus being more likely to effectively classify client data into a service plan to recomend.

Decision Tree: max_depth = 0.78
Random Forest: max_depth = 0.78 

## Software

**Tools:** _python_, _jupyter_

**Libraries:** _pandas_, _sklearn_
