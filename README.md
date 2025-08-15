# SMA_orbit_analysis
Satellite orbital stability analysis with SMA data – combining Random Forest classification and rule-based heuristics


# Overview
This project analyzes satellite orbital data, specifically the Semi-Major Axis (SMA) parameter, using both a Machine Learning approach (Random Forest Classifier) and a Heuristic approach for comparison. The goal is to classify and detect potential anomalies in orbital stability over time.

# 📂  Dataset
File: SMA_data.csv

# Columns:

Datetime – Time of observation (hh:mm:ss format).

SMA – Semi-Major Axis of the satellite’s orbit (in kilometers).

The Semi-Major Axis is a critical orbital parameter that determines the size of a satellite's orbit. Monitoring SMA over time can help detect orbital decay, drift, or other anomalies that may affect mission performance.

# 🛠 Methods Used
1. Machine Learning Approach
Model: RandomForestClassifier (Scikit-learn)

# Steps:

Data preprocessing and splitting into training/testing sets.

Training the Random Forest model on SMA readings.

Evaluating performance using:

Classification Report (Precision, Recall, F1-score)

Confusion Matrix

## 2. Heuristic Approach
Developed manually coded rules to classify SMA readings.

Serves as a baseline for comparing ML model performance.

# 📊 Results
Machine Learning Model: Achieved higher classification accuracy and better precision-recall trade-off compared to the heuristic method.

Heuristic Method: Provided reasonable but less consistent predictions.

Evaluation visuals (confusion matrix and metrics) are included in the notebook.


