## 3. Objective

The main objectives of this practical are:

- To understand Logistic Regression.
- To load and explore the Titanic dataset.
- To perform data preprocessing.
- To select relevant features.
- To perform train-test splitting.
- To train a Logistic Regression model.
- To make predictions.
- To calculate prediction probabilities.
- To evaluate the model using accuracy, confusion matrix and classification report.

## 4. Dataset

The dataset used in this practical is the Titanic dataset.

The dataset contains passenger information and survival status.

The target variable is:

- 0 - Not Survived
- 1 - Survived

Dataset file:

`train.csv`

## 5. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Visual Studio Code

## 6. Machine Learning Model

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for classification problems.

In this project, it is used for binary classification:

- Not Survived
- Survived

## 7. Project Workflow

The project follows these steps:

1. Load the Titanic dataset.
2. Understand the dataset.
3. Perform data preprocessing.
4. Select relevant features.
5. Encode categorical data where required.
6. Split the dataset into training and testing data.
7. Train the Logistic Regression model.
8. Make predictions.
9. Calculate prediction probabilities.
10. Evaluate the model.

## 8. Train-Test Split

The dataset was divided into:

- Training Samples: 712
- Testing Samples: 179

Training data is used to train the model, while testing data is used to evaluate the model.

## 9. Model Training

The Logistic Regression model is trained using the training dataset.

```python
model = LogisticRegression()
model.fit(X_train, y_train)
