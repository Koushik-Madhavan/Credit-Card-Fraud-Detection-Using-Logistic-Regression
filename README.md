# Credit Card Fraud Detection Using Logistic Regression

## Project Overview
This project involves building a credit card fraud detection system using logistic regression. The aim is to identify fraudulent transactions based on historical data, distinguishing between normal and fraudulent activities. This machine learning model will help in detecting anomalies and patterns that are commonly associated with fraudulent behavior in credit card transactions.

The dataset contains a distribution of normal and fraudulent transactions, and logistic regression is used to classify transactions as either "fraudulent" or "normal."

## Project Structure

- **Data Generation**: We generate a sample dataset with a similar distribution of normal and fraudulent transactions, ensuring a balanced representation of both classes.
  
- **Model Training**: Logistic regression is implemented to learn from the historical data and predict fraudulent activities based on transaction features.

- **Data Preprocessing**: The dataset undergoes preprocessing, including normalization and splitting into training and testing sets.

- **Model Evaluation**: The model's performance is evaluated based on metrics such as accuracy, precision, recall, and F1-score.

## Sample Dataset Overview
The dataset is split into two primary categories:

- **Normal Transactions**: Transactions that are typical and non-suspicious.
- **Fraudulent Transactions**: Transactions that are flagged as fraudulent based on unusual patterns or detected anomalies.

The distribution of these transactions is as follows:

- **Normal**: 85% of the dataset
- **Fraudulent**: 15% of the dataset

## How to Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
2. Install dependencies:
   ```bash
    pip install -r requirements.txt
3. Run the code:
   ```bash
    Execute the Python script to train the logistic regression model and analyze the results:
    python fraud_detection.py

## Key Features

- **Balanced Dataset**: Equal representation of normal and fraudulent transactions.
- **Logistic Regression Model**: A classification model based on logistic regression.
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score for evaluating the model.

## Conclusion
This project demonstrates the application of logistic regression in detecting fraudulent credit card transactions. By classifying transactions as either fraudulent or normal, the model can help banks and financial institutions reduce fraud-related losses and improve security.


