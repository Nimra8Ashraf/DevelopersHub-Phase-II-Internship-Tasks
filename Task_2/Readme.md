# End-to-End Machine Learning Pipeline for Customer Churn Prediction

## Project Overview

This project implements a complete end-to-end Machine Learning pipeline to predict customer churn using the Telco Customer Churn dataset. The pipeline is built using Scikit-learn's Pipeline API, enabling seamless preprocessing, model training, hyperparameter tuning, evaluation, and model deployment.

The objective is to create a reusable and production-ready machine learning workflow that automates the entire prediction process.

---

## Objectives

- Load and preprocess the Telco Customer Churn dataset.
- Handle missing values and encode categorical features.
- Scale numerical features using Scikit-learn Pipeline.
- Train multiple machine learning models.
- Optimize model performance using GridSearchCV.
- Evaluate the trained models using classification metrics.
- Export the complete pipeline using Joblib for future inference.

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer demographic information, subscribed services, account details, and whether the customer has churned.

**Target Variable:**
- Churn (Yes / No)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Matplotlib
- Seaborn

---

## Machine Learning Models

The following models were implemented and compared:

- Logistic Regression
- Random Forest Classifier

---

## Project Workflow

1. Import Required Libraries
2. Load Dataset
3. Data Cleaning
4. Feature Engineering
5. Data Preprocessing
   - Missing Value Handling
   - One-Hot Encoding
   - Feature Scaling
6. Create Scikit-learn Pipeline
7. Train Machine Learning Models
8. Hyperparameter Tuning using GridSearchCV
9. Evaluate Model Performance
10. Save the Best Pipeline using Joblib

---

## Pipeline Components

The Scikit-learn Pipeline includes:

- Data Preprocessing
- Feature Encoding
- Feature Scaling
- Machine Learning Model

Using a pipeline ensures that all preprocessing steps are automatically applied during both training and prediction.

---

## Hyperparameter Tuning

GridSearchCV is used to identify the optimal model parameters by performing cross-validation across multiple parameter combinations.

---

## Evaluation Metrics

The trained models are evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## Model Export

The best-performing pipeline is saved using Joblib.

Example:

```python
import joblib

joblib.dump(best_pipeline, "customer_churn_pipeline.pkl")
```

The saved pipeline can later be loaded without repeating preprocessing or retraining.

---

## Project Structure

```
Customer-Churn-Pipeline/
│
├── customer_churn_pipeline.ipynb
├── Telco-Customer-Churn.csv
├── customer_churn_pipeline.pkl
├── requirements.txt
├── README.md
└── images/
```

---

## Skills Demonstrated

- End-to-End Machine Learning Pipeline Development
- Data Preprocessing
- Feature Engineering
- Scikit-learn Pipeline API
- GridSearchCV Hyperparameter Tuning
- Model Evaluation
- Model Serialization using Joblib
- Production-Ready Machine Learning Workflow

---

## Future Improvements

- Add XGBoost and LightGBM models
- Build a Streamlit web application for predictions
- Deploy the model using Flask or FastAPI
- Integrate real-time customer churn prediction

---

## Author

**Nimra Ashraf**
