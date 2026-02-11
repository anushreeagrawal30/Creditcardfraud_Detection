📌 Overview

This project detects fraudulent credit card transactions using a Random Forest classifier. Since fraud cases are rare, the model was evaluated using F1-score and ROC-AUC instead of accuracy.

📂 Dataset
20,227 transactions
31 features
V1–V28 are PCA-transformed (anonymized) features
Class → Target (0 = Normal, 1 = Fraud)

⚙️ Approach
Removed missing values
Dropped id column
Train-test split (80-20)
Applied StandardScaler
Trained Random Forest (100 trees)
Used 5-fold cross-validation

📊 Results
Average F1-score ≈ 0.88
High recall for fraud detection
Strong ROC-AUC performance

🚀 Key Learnings
Handling imbalanced datasets
Importance of F1-score over accuracy
Ensemble learning using Random Forest
