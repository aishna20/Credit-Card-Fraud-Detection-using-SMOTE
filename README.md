💳 Credit Card Fraud Detection using SMOTE
📌 Project Overview

Credit card fraud is a major issue in financial systems, where fraudulent transactions are extremely rare compared to legitimate ones. This creates a highly imbalanced dataset, making it difficult for machine learning models to detect fraud effectively.

This project uses SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset and improve fraud detection performance.

🎯 Objectives
Detect fraudulent credit card transactions
Handle class imbalance using SMOTE
Compare model performance before and after SMOTE
Build a reliable fraud detection system
📂 Dataset
The dataset contains transactions made by European cardholders
Features are anonymized (V1, V2, ..., V28) using PCA
Includes:
Time
Amount
Class (0 = Legit, 1 = Fraud)
⚙️ Technologies Used
Python 🐍
Pandas & NumPy
Scikit-learn
Imbalanced-learn (SMOTE)
Matplotlib & Seaborn
🔄 Workflow
1. Data Preprocessing
Load dataset
Handle missing values (if any)
Normalize Amount and Time
2. Exploratory Data Analysis (EDA)
Class distribution analysis
Fraud vs Non-Fraud comparison
3. Handling Imbalance
Apply SMOTE to generate synthetic fraud samples
4. Model Training

Models used:

Logistic Regression
Random Forest

5. Model Evaluation

Metrics used:

Accuracy
Precision
Recall
F1-score
ROC-AUC Score
⚖️ Why SMOTE?

SMOTE helps in:

Balancing the dataset
Preventing model bias toward majority class
Improving recall for fraud detection
