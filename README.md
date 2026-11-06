# Hospital Readmission Risk Prediction Using MLP

## Project Overview

This project uses a Multi-Layer Perceptron (MLP) neural network to predict early hospital readmission within 30 days using the Diabetes 130-US Hospitals Dataset.

## Objectives

- Predict early hospital readmission.
- Address class imbalance.
- Compare multiple MLP architectures.
- Evaluate models using classification metrics.
- Analyze prediction errors and business implications.

## Models Implemented

- Baseline MLP
- Class-Weighted MLP
- Class-Weighted MLP with Early Stopping
- Dropout MLP with Early Stopping

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

## Best Model

The Dropout MLP achieved the highest recall and F1-score among the evaluated models.

- Recall: 53.51%
- F1-score: 25.97%
- ROC-AUC: 65.51%

## Project Structure

- `notebook/` – Complete implementation and model evaluation.
- `reports/` – Model evaluation, structured error analysis, and business findings.

## Limitations

This project is an educational prototype based on historical healthcare data. It has not undergone clinical validation and should not be used for real-world medical decisions.

## Technologies Used

Python, Pandas, NumPy, Scikit-learn, TensorFlow, Keras, Matplotlib, Seaborn, Google Colab.
