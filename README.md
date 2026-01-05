his project focuses on detecting fraudulent credit card transactions using Logistic Regression, a powerful algorithm widely used for binary classification tasks. The goal is to identify patterns that differentiate legitimate transactions from fraudulent ones, helping financial institutions minimize losses and improve security.

Project Overview
Credit card fraud is a major challenge in the financial industry. Fraudulent transactions are typically rare, making this a highly imbalanced classification problem.
In this project, we build a Logistic Regression model trained on a credit card dataset to classify transactions as:

0 → Legitimate
1 → Fraudulent

Project Workflow
1. Data Collection
The dataset used contains anonymized credit card transaction data with 30 features, including a binary target indicating fraud.
(Usually obtained from Kaggle's Credit Card Fraud Detection dataset.)

2. Data Preprocessing
Data preparation includes:

Handling missing values
Normalizing features (important for Logistic Regression)
Checking class imbalance
Splitting features and labels
Removing outliers (optional)


3. Splitting Training & Testing Data
The dataset is divided into:

Training Set (80%) – used to train the model
Testing Set (20%) – used to evaluate performance


4. Model Training
We train a Logistic Regression model, which works well for binary classification by estimating the probability of fraud using a sigmoid function.

5. Model Evaluation
We evaluate the model using:

Accuracy


These metrics give a clear understanding of how the model handles fraud detection, especially false positives vs. false negatives.
