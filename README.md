# Credit Card Fraud Detection using Machine Learning

## Project Overview

Credit Card Fraud Detection is a Machine Learning project developed to identify fraudulent credit card transactions using multiple classification algorithms. The project focuses on handling highly imbalanced data through preprocessing techniques and evaluating the performance of different machine learning models.

The project compares four supervised machine learning algorithms to determine their effectiveness in detecting fraudulent transactions while minimizing false positives and false negatives.

The implementation includes data preprocessing, feature scaling, class balancing using SMOTE, model training, evaluation, and visualization.

**Dataset Source**

Kaggle Credit Card Fraud Detection Dataset

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

# Features

- Detect fraudulent credit card transactions
- Compare four Machine Learning algorithms
- Handle highly imbalanced datasets using SMOTE
- Perform Exploratory Data Analysis (EDA)
- Apply feature scaling using RobustScaler
- Visualize fraud distribution
- Generate correlation heatmaps
- Plot confusion matrices
- Plot Precision-Recall Curves
- Generate classification reports
- Compare model performance

---

# Technologies Used

| Technology | Purpose |
|------------|-----------------------------|
| Python | Programming Language |
| Pandas | Data Processing |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-Learn | Machine Learning |
| Imbalanced-Learn (SMOTE) | Handle Class Imbalance |
| Jupyter Notebook | Model Development |

---

# Project Structure

```text
Credit_Card_Fraud_Detection/

├── Code/
│   ├── Credit Card Fraud Detection - Logistic Regression.ipynb
│   ├── Credit Card Fraud Detection - Decision Tree.ipynb
│   ├── Credit Card Fraud Detection - K Nearest Neighbor.ipynb
│   └── Credit Card Fraud Detection - Support Vector Machine.ipynb
│
├── README.md
├── LICENSE
├── .gitattributes
└── .gitignore
```

---

# Installation

Install the required libraries before running the notebooks.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn jupyter
```

---

# Dataset

The dataset is not included in this repository because it exceeds GitHub's file size limit.

Download the dataset from Kaggle:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

After downloading,

Create a folder named:

```text
data
```

Place the downloaded file inside it.

```text
Credit_Card_Fraud_Detection/

└── data/
      └── creditcard.csv
```

---

# How to Run

1. Clone this repository

```bash
git clone https://github.com/yuvakishore-tech/Credit_card_fraud_detection.git
```

2. Open the project folder.

3. Download the Kaggle dataset.

4. Place **creditcard.csv** inside the **data** folder.

5. Open any notebook from the **Code** folder using Jupyter Notebook or Visual Studio Code.

6. Run every notebook from the first cell to the last.

---

# Machine Learning Models Implemented

The following Machine Learning algorithms are implemented and compared.

| Model |
|--------|
| Logistic Regression |
| Decision Tree |
| K-Nearest Neighbor (KNN) |
| Support Vector Machine (SVM) |

Each notebook is implemented independently and contains complete preprocessing, training, prediction, evaluation, and visualization.

---

# Data Preprocessing

The following preprocessing steps are performed before model training.

- Missing value inspection
- Exploratory Data Analysis (EDA)
- Fraud distribution analysis
- Transaction amount visualization
- Correlation heatmap
- Feature scaling using RobustScaler
- Train-Test Split
- Class balancing using SMOTE

---

# Exploratory Data Analysis

The notebooks include:

- Dataset preview
- Dataset statistics
- Missing value analysis
- Fraud vs Non-Fraud distribution
- Transaction Amount Distribution
- Correlation Heatmap

---

# Model Evaluation

Each notebook evaluates the model using:

- Confusion Matrix
- Precision
- Recall
- F1 Score
- Precision-Recall Curve
- Classification Report

---

# Model Workflow

```text
Load Dataset
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Scaling
      │
      ▼
Train-Test Split
      │
      ▼
SMOTE Oversampling
      │
      ▼
Model Training
      │
      ▼
Prediction
      │
      ▼
Performance Evaluation
      │
      ▼
Visualization
```

---

# Best Model for Fraud Detection

Among the implemented models, **Support Vector Machine (SVM)** generally provides the strongest fraud detection capability because it creates an optimal decision boundary between fraudulent and legitimate transactions. When combined with feature scaling and class balancing techniques such as SMOTE, SVM is effective at identifying complex fraud patterns.

However, model performance depends on the dataset, preprocessing, and evaluation metric. For highly imbalanced datasets, metrics such as Precision, Recall, F1-score, and Precision-Recall AUC provide a more meaningful comparison than accuracy alone.

---

# Factors Affecting Fraud Detection

Several factors influence the performance of fraud detection models:

- Severe class imbalance between legitimate and fraudulent transactions
- Quality of feature scaling
- Oversampling technique (SMOTE)
- Choice of Machine Learning algorithm
- Hyperparameter tuning
- Decision threshold
- Feature correlation
- Noise and outliers in transaction data
- Train-Test data distribution
- Quality of preprocessing

---

# Visualizations Included

Each notebook contains:

- Fraud Distribution Plot
- Transaction Amount Distribution
- Correlation Heatmap
- Confusion Matrix
- Precision-Recall Curve

---

# Learning Outcomes

This project demonstrates:

- Data preprocessing
- Exploratory Data Analysis
- Handling imbalanced datasets
- Feature engineering
- Feature scaling
- Machine Learning model development
- Model comparison
- Classification evaluation
- Fraud detection techniques
- Data visualization
- Jupyter Notebook workflow

---

# Future Improvements

Possible enhancements include:

- Random Forest Classifier
- XGBoost Classifier
- LightGBM
- CatBoost
- Isolation Forest
- Autoencoder-based Fraud Detection
- Hyperparameter Optimization
- Model Deployment using Streamlit or Flask
- Real-Time Fraud Detection API

---

# License

This project is developed for educational purposes and internship portfolio demonstration.
