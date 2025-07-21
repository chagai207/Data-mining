# Customer Churn Prediction – Data Mining Project

This project focuses on predicting customer churn using various classification algorithms, implemented as part of a university-level data mining course. The objective is to analyze structured behavioral and demographic data, preprocess it effectively, and train predictive models to classify whether a customer is likely to churn.

## Project Objectives

- Perform end-to-end data mining on real-world customer data
- Engineer new features and apply dimensionality reduction (PCA)
- Handle imbalanced data with SMOTE
- Train and compare classifiers (Decision Tree, KNN, Random Forest, etc.)
- Use Grid Search and Cross Validation for model optimization
- Evaluate performance with metrics such as F1, Precision, Recall

## Dataset

- **Source**: A structured dataset including customer demographics and usage behavior
- **Size**: ~5000 samples, with a ~15% churn rate
- **Target column**: `Churn` (Yes/No)
- **Preprocessing included**:
  - Handling missing values
  - Feature encoding
  - PCA to reduce feature space

##  Technologies Used

- Python 3.x
- Google Colab / Jupyter Notebook
- `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`, `imblearn`

##  Files


├── notebooks/
│ └── churn_prediction.ipynb # Full project notebook
├── report/
│ └── final_report.pdf # Project documentation (Hebrew)
├── data/
│ └── sample.csv (optional) # Sample dataset or data source reference
├── requirements.txt # Python dependencies
└── README.md # This file

## 📈 Results Summary

The best-performing model (Random Forest with Grid Search) achieved:

- Accuracy: 0.92
- F1 Score: 0.89
- Balanced precision and recall


