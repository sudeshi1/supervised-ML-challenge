# Supervised Machine Learning - Predicting Credit Risk

**Goal**: To build a machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not.

![Loan GIF](/images/gif.gif)

## Background

LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loands as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API.

![GIF](/images/gif1.gif)

## Accomplishments

- Retrieving the data
- Preprocessing data: Converting catergorial data to numeric data
- Consider the models
- Scale the data
- Fit a LogisticRegression model & RandomForestClassifier model

![Models](/images/gif2.gif)

## Conclusions

- For the LogisticRegression Model, scaling the data with StandardScaler improved the testing prediction accuracy by over 15%
- LogisticRegression Model (scaled) proved to be the *most accurate* followed by RandomForestClassifier
- RandomForestClassifier (scaled & unsclaed) have *same degree of accuracy* across the testing and training dataset
- However, one thing to take note of is that RandomForestClassifier has an accuracy of *1.00* on the training dataset

![approved!](/images/gif3.gif)

