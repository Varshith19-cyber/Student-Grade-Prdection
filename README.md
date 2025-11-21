# Student Grade Prediction 🎓

Predict student performance (pass/fail + grade tendency) from academic and study-related features using a simple, end-to-end machine learning pipeline.

## Overview

This project uses a synthetic dataset of student records (attendance, internal marks, assignments, study hours) to train and evaluate classification models. It demonstrates a realistic workflow: data generation → preprocessing → model training → evaluation → single-record prediction.

## Features

- Synthetic dataset generator script
- Clean tabular ML pipeline
- Models:
  - Logistic Regression
  - Random Forest Classifier
- Evaluation with precision, recall, F1-score
- JSON-based prediction script to infer pass/fail for a single student

## Tech Stack

- Python
- NumPy, Pandas
- Scikit-learn
- Joblib

## Project Structure

```text
student-grade-prediction/
  ├─ data/
  │   ├─ generate_synthetic_data.py
  │   └─ students_raw.csv
  ├─ src/
  │   ├─ preprocess.py
  │   ├─ train.py
  │   └─ predict.py
  ├─ models/
  │   └─ random_forest_student_pass.pkl
  ├─ sample_input.json
  ├─ requirements.txt
  └─ README.md
