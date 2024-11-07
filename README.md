# Fraud Detection Project

This project uses machine learning techniques to detect fraudulent transactions in credit card data. The focus is on identifying potential outliers and anomalies in the dataset using models like Isolation Forest and Local Outlier Factor.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling Approach](#modeling-approach)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The goal of this project is to classify transactions as fraudulent or non-fraudulent using various anomaly detection techniques. The project explores data preprocessing, feature scaling, and model evaluation using classification metrics.

## Dataset
The project utilizes the `creditcard.csv` dataset, which contains anonymized features of credit card transactions, with the class label indicating whether a transaction is fraudulent (1) or non-fraudulent (0).

## Installation
To run this project, you'll need Python 3.x and the following libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## Usage
1. **Load the Data**: The dataset should be saved as `creditcard.csv`.
2. **Run the Notebook**: Execute each cell sequentially to load data, preprocess, and train models.

### Step-by-Step Guide
- **Data Loading**: Load the dataset and perform initial checks.
- **Exploratory Data Analysis (EDA)**: Initial insights into data shape, structure, and missing values.
- **Data Preprocessing**: Scale the features for model input.
- **Modeling**: 
    - **Isolation Forest**
    - **Local Outlier Factor**
    - **One-Class SVM**
- **Evaluation**: Evaluate using metrics like accuracy, F1 score, and confusion matrix.

## Modeling Approach
This project uses three main approaches to detect anomalies:

1. **Isolation Forest**: An unsupervised learning algorithm used to detect anomalies in data by isolating observations.
2. **Local Outlier Factor**: Measures the local deviation of a data point compared to its neighbors to identify outliers.
3. **One-Class SVM**: A support vector machine model configured for anomaly detection to classify data points as similar or different from the majority.

## Results
Each model's performance is evaluated based on accuracy, F1 score, and confusion matrix analysis.

- **Isolation Forest** achieved an F1 score of ...
- **Local Outlier Factor** achieved an F1 score of ...
- **One-Class SVM** achieved an F1 score of ...

## License
This project is open-source. Feel free to use, modify, and distribute as per the project's license.
