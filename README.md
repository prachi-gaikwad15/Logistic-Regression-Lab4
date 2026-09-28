# Titanic Survival Prediction using Logistic Regression

## Lab 4 – Logistic Regression

## Overview

This project demonstrates the implementation of a Logistic Regression machine learning model using the Titanic dataset. The objective is to predict whether a passenger survived or did not survive based on the available passenger information.

The project follows the complete machine learning workflow, including data loading, data preprocessing, feature selection, train-test splitting, model training, prediction, and model evaluation.

## Objective

The main objectives of this practical are:

- To understand Logistic Regression.
- To load and work with the Titanic dataset.
- To preprocess the dataset for machine learning.
- To divide the dataset into training and testing data.
- To train a Logistic Regression model.
- To make predictions using the trained model.
- To evaluate the performance of the model using accuracy, confusion matrix, and classification report.

## Dataset

The dataset used in this project is the **Titanic Dataset**.

The dataset contains information about passengers such as passenger details and survival status.

The target variable is:

- **0 – Not Survived**
- **1 – Survived**

The dataset used for the practical is provided in:

`train.csv`

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- VS Code

## Machine Learning Model

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for classification problems.

In this project, Logistic Regression is used to classify Titanic passengers into two categories:

- Not Survived
- Survived

## Project Workflow

The project follows these major steps:

1. Import required Python libraries.
2. Load the Titanic dataset.
3. Explore and understand the dataset.
4. Perform data preprocessing.
5. Select the required features and target variable.
6. Split the dataset into training and testing sets.
7. Train the Logistic Regression model.
8. Make predictions on the test dataset.
9. Evaluate the model performance.
10. Display the final results.

## Train-Test Split

The dataset is divided into two parts:

- **Training Samples:** 712
- **Testing Samples:** 179

The training data is used to train the Logistic Regression model, while the testing data is used to evaluate how well the trained model performs on unseen data.

## Model Training

After preprocessing the dataset and performing the train-test split, the Logistic Regression model is trained using the training dataset.

The trained model is then used to predict the survival status of passengers in the testing dataset.

## Model Prediction

The trained Logistic Regression model predicts whether each passenger:

- **Survived**
- **Did Not Survive**

The predicted values are compared with the actual values from the test dataset.

## Model Evaluation

The performance of the model is evaluated using:

### 1. Accuracy

The model achieved approximately:

**81.01% Accuracy**

### 2. Confusion Matrix

The confusion matrix obtained from the model is:

```text
[[90 15]
 [19 55]]
