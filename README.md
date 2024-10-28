# Spam Mail Prediction using Logistic Regression

This repository contains a project for predicting whether an email is spam or not using a Logistic Regression model. The project converts email messages into numerical features using TF-IDF Vectorization for classification.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)

## Introduction

Spam Mail Prediction is an important task for managing unwanted emails and improving the quality of email filtering. This project aims to build a machine learning model to classify emails as spam or not spam based on text-based features extracted from email content.

## Dataset

The dataset used in this project contains email messages labeled as spam or not spam. It has been split into training and testing sets to evaluate the model's performance.

## Installation

To run this project, you need to have Python installed on your machine. You can install the required dependencies using `pip`.

```
pip install numpy pandas scikit-learn
```

Requirements
Python 3.x
NumPy
Pandas
Scikit-learn

## Usage

1. Clone the repository to your local machine:

```
   git clone https://github.com/srijosh/Spam-Mail-Prediction-using-Logistic-Regression.git
```

2. Navigate to the project directory:
   cd Spam-Mail-Prediction-using-Logistic-Regression

3. Open and run the Jupyter Notebook:
   jupyter notebook Spam_Mail_Prediction.ipynb

## Model

The model used in this project is a Logistic Regression classifier. The email data is preprocessed by converting the text into numerical features using TF-IDF Vectorization. Key steps include:

# Data Preprocessing

- TF-IDF Vectorization: Converting email content into numerical features based on term frequency and inverse document frequency.
  Model Training
- Logistic Regression: A linear model is trained on the processed data to classify emails as spam or not spam.

## Evaluation

The model is evaluated using the following metric:

- Accuracy Score: Measures the percentage of correct predictions made by the model. A higher accuracy score indicates better performance in predicting spam and non-spam emails.
