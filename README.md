# Random Forest Machine Failure Prediction

A machine learning project predicting industrial machine failure using a Random Forest classifier, trained on the AI4I 2020 Predictive Maintenance dataset.

## Overview
This project explores predictive maintenance — using sensor and operational data to predict whether a machine is likely to fail, allowing for proactive maintenance instead of reactive repairs.

## Results
- **Model:** Random Forest Classifier
- **Performance:** ~0.97 ROC-AUC

## Dataset
`Machine_failure.csv` — the AI4I 2020 Predictive Maintenance dataset (10,000 rows), containing sensor readings (air/process temperature, rotational speed, torque, tool wear) and failure mode labels (TWF, HDF, PWF, OSF, RNF).

## Tech Stack
- Python
- Scikit-Learn
- NumPy / Pandas
- Matplotlib / Seaborn (for visualization)

## Approach
1. Data cleaning and exploratory analysis
2. Feature selection based on sensor readings (torque, tool wear, temperature, etc.)
3. Train/test split
4. Random Forest model training and hyperparameter tuning
5. Evaluation using ROC-AUC and confusion matrix

## Running Locally
```bash
git clone https://github.com/munkhbrave22/random-forest-machine-failure-prediction.git
cd random-forest-machine-failure-prediction
pip install -r requirements.txt
jupyter notebook
```

## Files
```
├── machine_failure_prediction.ipynb
├── requirements.txt
└── data/ (dataset, if included)
```
