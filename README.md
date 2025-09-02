**Predicting Bankruptcy & Detecting Money Laundering using Machine Learning**
_Overview_

This project implements Machine Learning models to:

**Predict company bankruptcy based on financial indicators.**

**Detect money laundering activities in Bitcoin blockchain transactions.**

*The work is based on replicating and extending results from two research papers:*

1. Cognitive Modelling of Bankruptcy Risk (IEEE, 2024)

2. Machine Learning Model for Detecting Money Laundering in Bitcoin Blockchain Transactions (JAAI, 2024)

**Technologies Used**

**Python (Data Analysis & Modeling)**

**Scikit-learn (ML Algorithms)**

**Pandas, NumPy (Data Handling)**

**Matplotlib, Seaborn (Visualization)**

**Datasets**

US Company Bankruptcy Prediction Dataset

Source: Kaggle

Size: 78,682 instances, 21 attributes

Target: status_label (alive: 1, failed: 0)

Elliptic Dataset for Bitcoin Money Laundering Detection

Source: Kaggle

Size: 203,768 instances, 167 attributes

Labels: illicit (1), licit (2), unknown (0)

**Objectives**
1. Bankruptcy Prediction

Predict whether a company will fail or survive using financial ratios and company attributes.

2. Money Laundering Detection

Identify illicit Bitcoin transactions using transaction metadata.

**Machine Learning Models**
For Bankruptcy Prediction

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

Support Vector Machine (Linear & RBF)

Random Forest
