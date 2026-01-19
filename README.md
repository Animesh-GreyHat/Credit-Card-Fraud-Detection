# Credit-Card-Fraud-Detection
Machine Learning project to detect credit card fraud using Decision Tree, Random Forest &amp; Naive Bayes.

# Credit Card Fraud Detection

## Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset contains real credit card transactions labeled as fraud or non-fraud. Fraud transactions are rare, creating an imbalanced dataset.

## Dataset
- Source: Kaggle (Credit Card Fraud Detection)
- Columns: 30 features including anonymized V1-V28, Time, Amount, and Class (fraud label)
- Class: 0 = Normal, 1 = Fraud

## Steps Performed
1. **Data Exploration**
   - Checked first few rows, data types, and class distribution.
   - Identified imbalance in the dataset.

2. **Data Preprocessing**
   - Scaled the `Amount` column.
   - Dropped unnecessary columns (`Time`, original `Amount`).

3. **Train-Test Split**
   - Split data into training (70%) and testing (30%) sets.
   - Stratified split to maintain class distribution.

4. **Machine Learning Models**
   - **Decision Tree**
   - **Random Forest** (best performing model)
   - **Naive Bayes**
   - **Isolation Forest** (for outlier detection)

5. **Evaluation**
   - Classification report: Precision, Recall, F1-score
   - Confusion matrix: TP, FP, TN, FN
   - ROC-AUC score
   - Feature importance visualization (Random Forest)

## Key Findings
- Random Forest performed best with highest recall for fraud detection.
- Feature importance highlighted which transaction features contribute most to detecting fraud.
- Outlier detection can also identify rare fraudulent transactions.

## How to Run
1. Clone this repository
2. Open `Credit_Card_Fraud_Detection.ipynb` in Jupyter Notebook
3. Run step-by-step to see code, outputs, and graphs
4. Alternatively, use [nbviewer](https://nbviewer.org) to view online

## Visualization
- Confusion matrix heatmap
- Feature importance bar plot

