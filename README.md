# German Credit Risk Analysis

## Overview

This project applies data mining and machine learning techniques to the Statlog (German Credit Data) dataset to analyze and classify credit risk.

The analysis includes data preprocessing, exploratory data analysis, classification, regression, clustering, feature selection, feature engineering, and additional validation experiments.

## Dataset

The project uses the Statlog (German Credit Data) dataset from the UCI Machine Learning Repository.

The dataset contains 1,000 credit applications and includes numerical and categorical attributes describing applicants and their credit characteristics.

The dataset files used in the analysis are included in the `data/` directory.

## Methods

### Data Preprocessing and Exploratory Data Analysis

- Data loading and preparation
- Encoding of categorical variables
- Exploratory data analysis
- Class distribution analysis
- Correlation analysis
- Outlier analysis
- Feature scaling where required

### Classification

Three classification techniques were evaluated:

- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

The classification analysis includes:

- Confusion matrices
- Precision
- Recall
- F1-score
- Accuracy
- ROC-AUC
- Precision-Recall analysis
- Cost-sensitive classification using `class_weight='balanced'`
- Threshold tuning
- Feature importance and predictor interpretation

### Regression

Regression techniques were used to investigate relationships between credit-related variables and the selected numerical target.

### Clustering

Two clustering approaches were evaluated:

- K-Means
- DBSCAN

Cluster quality was assessed using internal validation measures, including silhouette score and the Davies-Bouldin index.

### Additional Experiments

Additional experiments investigate the effects of feature selection, feature engineering, and transformations on model performance.

## Project Structure

```text
german-credit-risk-analysis/
│
├── data/
│   ├── german.data
│   ├── german.data-numeric
│   ├── german.word
│   └── Index
│
├── figures/
│   └── Generated graphs and visualizations
│
├── german_credit_risk_analysis.ipynb
│   └── Complete data mining and machine learning analysis
│
├── credit_risk_documentation.pdf
│   └── Final project report
│
├── README.md
└── .gitignore
