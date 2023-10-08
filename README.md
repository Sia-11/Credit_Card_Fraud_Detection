# Credit Card Fraud Detection

Credit Card Fraud Detection is a Python project that focuses on identifying fraudulent credit card transactions using machine learning algorithms. This project aims to provide a reliable tool for financial institutions and businesses to automatically detect and prevent fraudulent transactions, ultimately saving money and protecting customers.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Model Selection](#model-selection)
- [Evaluation](#evaluation)
- [License](#license)

## Overview

Credit card fraud is a significant problem in the world of finance, costing billions of dollars each year. This project utilizes machine learning techniques to predict and classify credit card transactions as either fraudulent or legitimate. The goal is to provide a solution that can automatically flag suspicious transactions for further review.

## Features

- Data preprocessing: Includes data cleaning, scaling, and splitting into training and testing sets.
- Model training: Utilizes machine learning algorithms to build predictive models.
- Model evaluation: Measures the model's performance using appropriate metrics.
- Fraud prediction: Provides a tool for real-time fraud prediction based on transaction data.

## Dataset

The dataset used for this project is sourced from Kaggle and contains the following columns: Time, V1-V28 (features obtained through PCA transformation for privacy reasons), Amount, Class (0 for legitimate transactions, 1 for fraudulent transactions).

## Project Structure

The project is structured as follows:

- `credit_card_fraud_detection.ipynb`: Jupyter Notebook containing the code and explanations for data preprocessing, model training, and evaluation.
- `requirements.txt`: Lists the required Python packages for running the project.

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine:

`git clone https://github.com/Sia-11/Credit_Card_Fraud_Detection.git`

2. Navigate to the project directory

3. Open the Jupyter Notebook `credit_card_fraud_detection.ipynb` to explore the code and execute it step by step.

4. Follow the instructions and comments in the notebook to preprocess the data, train machine learning models, and evaluate their performance.

5. Make use of the trained models for predicting fraud in new transactions or real-time scenarios.

## Model Selection

The project includes the use of multiple machine learning algorithms for model selection, including but not limited to:

- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier

You can select the model that best fits your specific requirements and dataset.

## Evaluation

The models' performance is evaluated using common classification metrics, including:

- Accuracy
- Classification Report

The choice of the evaluation metric depends on the specific goals of your fraud detection system.

## License

This project is licensed under the [MIT License](LICENSE).
