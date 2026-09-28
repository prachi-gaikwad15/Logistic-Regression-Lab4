# Titanic Survival Prediction using Logistic Regression

## Lab 4 - Logistic Regression

---

## 1. Overview

This project is based on the implementation of a Logistic Regression machine learning model using the Titanic dataset.

The main objective of this practical is to develop a binary classification model that can predict whether a passenger survived the Titanic disaster or did not survive.

The project demonstrates the complete machine learning workflow starting from loading the dataset and understanding the data to preprocessing, feature selection, train-test splitting, model training, prediction, probability estimation, and model evaluation.

Logistic Regression is used because the target variable contains two possible outcomes:

- 0 - Not Survived
- 1 - Survived

The trained model is evaluated using accuracy, confusion matrix, precision, recall, F1-score, and classification report.

---

## 2. Problem Statement

The Titanic dataset contains information about passengers who travelled on the RMS Titanic.

The task is to build a machine learning classification model that can learn from passenger information and predict whether a passenger survived or did not survive.

The problem can be represented as:

```text
Passenger Information
        |
        v
Data Preprocessing
        |
        v
Feature Selection
        |
        v
Train-Test Split
        |
        v
Logistic Regression
        |
        v
Survival Prediction
        |
        v
Model Evaluation
