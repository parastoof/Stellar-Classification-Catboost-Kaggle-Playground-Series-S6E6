# Stellar Classification | Kaggle Playground Series S6E6

This repository contains my solution for the Kaggle Playground Series S6E6 competition, where the objective is to predict the stellar class (GALAXY, STAR, or QSO) using astronomical observations.

## Project Overview

* Exploratory Data Analysis (EDA)
* Data preprocessing and feature inspection
* CatBoost multiclass classification
* Hyperparameter tuning
* Evaluation using Balanced Accuracy (competition metric)
* Submission file generation for Kaggle

## Technologies

* Python
* Pandas
* Scikit-learn
* CatBoost

## Model

The final solution uses a CatBoostClassifier with GPU acceleration and tuned hyperparameters, achieving a validation Balanced Accuracy of approximately **0.9503**.

## Competition

Kaggle Playground Series – Season 6, Episode 6: Stellar Classification


├── kaggle_stellar_classification_catboost.ipynb
├── README.md
└── requirements.txt
