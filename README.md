# Titanic Survival Prediction using Logistic Regression

## Lab 4 - Logistic Regression

## 1. Overview

This project is based on the implementation of a Logistic Regression machine learning model using the Titanic dataset.

The main objective of this practical is to develop a binary classification model that can predict whether a passenger survived the Titanic disaster or did not survive.

The project demonstrates the complete machine learning workflow starting from loading the dataset and understanding the data to data preprocessing, feature selection, train-test splitting, model training, prediction, probability estimation, and model evaluation.

Logistic Regression is used because the target variable contains two possible outcomes:

- 0 - Not Survived
- 1 - Survived

The trained model is evaluated using accuracy, confusion matrix, precision, recall, F1-score, and classification report.

## 2. Problem Statement

The Titanic dataset contains information about passengers who travelled on the RMS Titanic.

The task is to build a machine learning classification model that can learn from passenger information and predict whether a passenger survived or did not survive.

The problem can be represented as:

Passenger Information
        |
        ↓
Data Preprocessing
        |
        ↓
Feature Selection
        |
        ↓
Train-Test Split
        |
        ↓
Logistic Regression
        |
        ↓
Survival Prediction
        |
        ↓
Model Evaluation

## 3. Objective

The main objectives of this practical are:

- To understand the concept of Logistic Regression.
- To load and explore the Titanic dataset.
- To perform data preprocessing.
- To select relevant features.
- To prepare data for machine learning.
- To divide the dataset into training and testing sets.
- To train a Logistic Regression model.
- To predict passenger survival.
- To calculate prediction probabilities.
- To evaluate the performance of the model.
- To understand classification metrics.

## 4. Dataset

The dataset used in this practical is the Titanic dataset.

The dataset contains information about passengers travelling on the Titanic and whether they survived the disaster.

The target variable is:

- 0 - Not Survived
- 1 - Survived

Dataset file:

train.csv

The dataset is used for performing data preprocessing, feature selection, model training, testing, and evaluation.

## 5. Technologies Used

The following technologies and libraries are used:

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Visual Studio Code

## 6. Machine Learning Model

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm used mainly for classification problems.

In this project, Logistic Regression is used to predict whether a Titanic passenger survived or did not survive.

The model performs binary classification with two possible classes:

- 0 - Not Survived
- 1 - Survived

The model learns patterns from the training data and uses those patterns to predict the class of passengers in the testing data.

## 7. Project Workflow

The complete machine learning workflow followed in this project is:

1. Load the Titanic dataset.
2. Understand the dataset.
3. Perform data preprocessing.
4. Select relevant features.
5. Prepare input and target variables.
6. Split the data into training and testing sets.
7. Create the Logistic Regression model.
8. Train the model.
9. Make predictions.
10. Calculate prediction probabilities.
11. Evaluate model accuracy.
12. Generate confusion matrix.
13. Generate classification report.
14. Perform prediction on new passenger data.

## 8. Data Preprocessing

Data preprocessing is performed before training the machine learning model.

The preprocessing stage prepares the dataset so that it can be used by the Logistic Regression algorithm.

The main steps include:

- Selecting required columns.
- Handling required data values.
- Preparing input features.
- Preparing the target variable.
- Converting data into a suitable format.
- Preparing categorical data where required.

The target variable used for prediction is:

Survived

## 9. Feature Selection

Feature selection is the process of selecting the important input variables required for prediction.

The selected passenger information is used as input features for the Logistic Regression model.

The target variable is:

Survived

The selected features are used to train the model and predict the survival status of passengers.

## 10. Train-Test Split

The dataset is divided into training and testing datasets.

The training dataset is used to train the Logistic Regression model.

The testing dataset is used to evaluate how well the trained model performs on unseen data.

The dataset was divided into:

- Training Samples: 712
- Testing Samples: 179

The train-test split helps in evaluating the model using data that was not used during training.

## 11. Model Training

The Logistic Regression model is created and trained using the training dataset.

The model learns the relationship between the selected passenger features and the survival status.

The model training process is performed using:

model = LogisticRegression(max_iter=1000)
model.fit(X_train, y_train)

After training, the model is ready to make predictions on the testing dataset.

## 12. Model Prediction

After training the model, predictions are made using the testing dataset.

The prediction is performed using:

y_pred = model.predict(X_test)

The model predicts one of the two classes:

- 0 - Not Survived
- 1 - Survived

These predictions are then compared with the actual values to evaluate the model.

## 13. Prediction Probability

The trained Logistic Regression model can also provide the probability of each class.

This is performed using:

y_probability = model.predict_proba(X_test)

The prediction probability provides the probability of:

- Not Survived
- Survived

This helps in understanding how confident the model is about its predictions.

## 14. New Passenger Prediction

The trained Logistic Regression model can also be used to predict the survival status of a new passenger.

The prediction includes:

- Predicted survival status
- Probability of not surviving
- Probability of surviving

This demonstrates how a trained machine learning model can be used to make predictions on new data.

## 15. Model Evaluation

The performance of the Logistic Regression model is evaluated using different classification metrics.

The following evaluation methods are used:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score
- Classification Report

These metrics help to understand the performance of the trained model.

## 16. Accuracy

Accuracy represents the percentage of correct predictions made by the model.

The Logistic Regression model achieved:

81.01% accuracy

Model summary:

- Training Samples: 712
- Testing Samples: 179
- Accuracy: 81.01%

## 17. Confusion Matrix

A confusion matrix is used to compare the actual class values with the predicted class values.

The confusion matrix obtained from the model is:

[[90 15]
 [19 55]]

The confusion matrix helps to understand the number of correct and incorrect predictions for both classes.

## 18. Classification Report

The classification report provides detailed performance metrics for each class.

It includes:

- Precision
- Recall
- F1-score
- Support

The classification report is generated for both:

- Not Survived
- Survived

The obtained results are approximately:

Not Survived:
- Precision: 0.83
- Recall: 0.86
- F1-score: 0.84
- Support: 105

Survived:
- Precision: 0.79
- Recall: 0.74
- F1-score: 0.76
- Support: 74

Overall Accuracy: 0.81

## 19. Precision

Precision represents the proportion of correctly predicted observations among all observations predicted as a particular class.

The obtained precision values are:

- Not Survived: 0.83
- Survived: 0.79

## 20. Recall

Recall represents the proportion of correctly identified actual observations of a class.

The obtained recall values are:

- Not Survived: 0.86
- Survived: 0.74

## 21. F1-Score

F1-score is a metric that combines precision and recall.

The obtained F1-score values are:

- Not Survived: 0.84
- Survived: 0.76

## 22. Model Performance Summary

TITANIC LOGISTIC REGRESSION MODEL

Training Samples: 712
Testing Samples: 179
Accuracy: 81.01%

The model achieved an accuracy of approximately 81.01% on the testing dataset.

## 23. Project Structure

Logistic-Regression-Lab4/

├── Logistic_Regression_Lab4.ipynb
├── Logistic_Regression_Lab4.html
├── Logistic_Regression_Lab4.pdf
├── train.csv
└── README.md

## 24. How to Run

Follow these steps to run the project:

1. Download or clone the repository.
2. Open the project in Visual Studio Code or Jupyter Notebook.
3. Make sure Python is installed.
4. Install the required Python libraries.
5. Open Logistic_Regression_Lab4.ipynb.
6. Select the appropriate Python environment/kernel.
7. Run the notebook cells from top to bottom.

Required libraries:

- pandas
- numpy
- matplotlib
- scikit-learn
- jupyter

## 25. Key Learning Outcomes

Through this practical, the following machine learning concepts were learned:

- Data preprocessing
- Feature selection
- Categorical data handling
- Train-test splitting
- Binary classification
- Logistic Regression
- Model training
- Model prediction
- Prediction probabilities
- Accuracy evaluation
- Confusion matrix
- Classification report
- Precision
- Recall
- F1-score
- Prediction on new data

## 26. Conclusion

In this practical, a Logistic Regression machine learning model was successfully implemented using the Titanic dataset.

The complete machine learning workflow was performed, including data preprocessing, feature selection, train-test splitting, model training, prediction, probability estimation, and model evaluation.

The model achieved an accuracy of approximately 81.01%.

The practical demonstrates how Logistic Regression can be used for binary classification and how different evaluation metrics can be used to understand model performance.

## 27. Author

Prachi Gaikwad

BCA Student
MIT World Peace University

GitHub: prachi-gaikwad15

## 28. Lab Information

Practical: Lab 4
Topic: Logistic Regression
Dataset: Titanic Dataset
Model: Logistic Regression
Problem Type: Binary Classification
Accuracy: 81.01%
