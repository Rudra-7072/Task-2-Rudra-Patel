# PROJECT 2

# DATA CLASSIFICATION USING AI

### *Using K-Nearest Neighbors (KNN) Algorithm on the Iris Dataset*

## Introduction

This project focuses on building a basic AI classification model using the Iris dataset. The K-Nearest Neighbors (KNN) algorithm is used to classify flowers into different species based on their characteristics. The project demonstrates the fundamentals of supervised machine learning and data classification.

## Objective

* To load and understand a dataset.
* To split the data into training and testing sets.
* To apply a classification algorithm.
* To evaluate the performance of the AI model.

## Technologies Used

* Python 3
* Scikit-learn Library

## Project Description

The Iris dataset is loaded using the Scikit-learn library. The data is standardized using `StandardScaler` to improve model performance. The dataset is then divided into training and testing sets.

A KNN classifier with `k = 5` is trained using the training data. After training, the model predicts the classes of the test data. The model's performance is evaluated using a confusion matrix and a classification report.

## Features

* Uses the Iris dataset.
* Data preprocessing with feature scaling.
* Training and testing data split.
* KNN classification algorithm.
* Model evaluation using confusion matrix and classification report.

## How to Run

1. Install Python and Scikit-learn.
2. Open the project folder.
3. Run the following command:

```bash
python "Project 2.py"
```

## Sample Output

```text
Confusion Matrix:
[[10  0  0]
 [ 0  9  0]
 [ 0  1 10]]

Classification Report:
Displays Precision, Recall, F1-Score and Accuracy for the Iris dataset.
```

## Conclusion

This project successfully demonstrates the implementation of an AI-based data classification model using the K-Nearest Neighbors algorithm. It covers important machine learning concepts such as data preprocessing, model training, prediction, and performance evaluation. This project provides a strong foundation for understanding supervised learning techniques and real-world AI applications.
