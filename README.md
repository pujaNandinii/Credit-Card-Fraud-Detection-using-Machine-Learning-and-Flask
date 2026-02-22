# Credit Card Fraud Detection using Machine Learning & Flask

A Machine Learning based web application that detects fraudulent credit card transactions.  
Built using Python, Flask, and a trained ML classification model.

---

## Project Overview

This project uses a trained machine learning model to predict whether a credit card transaction is fraudulent or legitimate.  
The web interface allows users to input transaction details and receive real-time predictions.

---

## Tech Stack

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- HTML / CSS
- Machine Learning (Classification Model)

---

## Installation & Setup

### Clone the Repository
git clone https://github.com/your-username/your-repo-name.git<br>
cd credit_card_fraud_detection

### Create Virtual Environment
conda create -n fraudenv python=3.8<br>
conda activate fraudenv

### Install Dependencies
pip install -r requirements.txt

### Run the Application
python app.py<br>
Open your browser and go to:<br>
http://127.0.0.1:5000/

---

## Model Information

- Type: Supervised Learning
- Problem: Binary Classification
- Output:
  - 0 → Legitimate Transaction
  - 1 → Fraudulent Transaction

---

## Input Requirements

The trained model expects 30 input features corresponding to the transaction dataset.

To get a prediction result:

1. Enter all 30 feature values

2. These represent the transaction features used by the trained machine learning model

3. After entering all 30 values, click the Predict button

4. Receive a binary classification result:

0 → Legitimate Transaction

1 → Fraudulent Transaction

Incomplete input will not generate a valid prediction.



