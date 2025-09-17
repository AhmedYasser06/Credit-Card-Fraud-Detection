# Credit Card Fraud Detection  

## 📌 Project Description  
This project provides an **end-to-end Credit Card Fraud Detection system** using advanced machine learning and ensemble techniques. It covers **data preprocessing, class balancing, hyperparameter tuning, model training, evaluation, and comparison** to handle the challenges of highly imbalanced fraud datasets.  

---
## 📂 Project Structure

```
Credit-Card-Fraud-Detection/
│
├── config/                       # Configuration files (parameters, paths, settings)
├── data/                         # Raw and processed datasets
├── docs/                         # Documentation, reports, and notes
├── models/                       # Saved trained models
├── __pycache__/                  # Cached Python files
├── credit_fraud_utils_helper.py  # Utility functions (helpers, preprocessing)
├── credit_fraud_utils_data.py    # Data handling and feature engineering
├── credit_fraud_utils_eval.py    # Evaluation metrics and visualization
├── credit_fraud_train.py         # Main training pipeline
├── EDA.ipynb                     # Exploratory Data Analysis notebook
└── README.md                    # Documentation
```
---
## 🔹 Key Highlights  

### 🔧 Data Handling & Preprocessing  
- Scaling with different techniques (e.g., **RobustScaler**).  
- Balancing imbalanced datasets with **oversampling, undersampling, SMOTE**, and more.  

### 🤖 Machine Learning Models  
- **Random Forest** (RandomizedSearch hyperparameter tuning).  
- **Logistic Regression** (GridSearch optimization).  
- **K-Nearest Neighbors (KNN)** (randomized parameter search).  
- **Neural Network (MLPClassifier)** with configurable layers, activations, and solvers.  
- **Voting Classifier** (ensemble of Random Forest, Logistic Regression, and Neural Network).  

### 📊 Model Evaluation  
- Metrics: **Precision, Recall, F1-score, ROC-AUC**, and threshold tuning.  
- Automated **comparison tables** and **visualization plots** for model benchmarking.  

### ⚙️ Configurable Workflow  
- Controlled via **YAML config files** (`config.yml`, `trainer_config.yml`).  
- Enable/disable models, adjust balancing strategies, and fine-tune hyperparameters.  

---
## 📤 Outputs  
- Trained models saved with **timestamps** in `models/`.  
- Evaluation plots for **performance analysis**.  
- Markdown-formatted **model comparison reports**.  

---

<img width="1392" height="284" alt="Screenshot 2025-09-17 071445" src="https://github.com/user-attachments/assets/3b620d7b-7560-40f0-b4f5-31b2cab6bf9c" />
