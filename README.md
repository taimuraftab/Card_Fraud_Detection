# Credit Card Fraud Detection

A machine learning project to detect fraudulent transactions using classification model. The goal is to build a reliable system that minimizes false positives while effectively catching fraud.

## Project Overview

- **Built a fraud detection model** using **RandomForestClassifier**.
- **Achieved 99% accuracy, precision, and recall**.
- **Evaluated model performance** using classification reports, ROC curve, and AUC score.

## Dataset

- **Source:** Kaggle (Credit Card Fraud Detection Dataset 2023)
- **Total Transactions:** 568630
- **Class Distribution:**  
  - `0` (Non-Fraud)
  - `1` (Fraud)
- **Key Features:**  
  - Time, Amount, and 28 anonymized numerical variables.

## Data Processing

- **Scaled numerical features** with `StandardScaler`.

## Model Performance

| Metric       | Score |
|-------------|------|
| **Model Used** | Random Forest |
| **Training Accuracy** | 98.64% |
| **Test Accuracy**  | 98.56% |
| **Precision** | 99% |
| **Recall**    | 99% |
| **F1-Score**  | 99% |
| **AUC Score** | **0.9995** |

## ROC Curve & AUC Score

- The model achieved an **AUC Score of 0.9995**, indicating near-perfect fraud detection.
- The **ROC Curve confirms effective classification**.

##  How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/taimuraftab/Card_Fraud_Detection.git
