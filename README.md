# Home Credit Default Risk

## Table of Contents
- [Overview](#overview)
- [Objective](#objective)
- [Steps](#steps)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Machine Learning Techniques](#machine-learning-techniques)
- [Evaluation Results](#evaluation-results)
- [System Flowchart](#system-flowchart)
- [Evaluation Metrics](#evaluation-metrics)

## Overview
Many individuals struggle to obtain loans due to insufficient or non-existent credit histories. **Home Credit** aims to enhance financial inclusion for the unbanked population by offering a secure and positive borrowing experience. This project leverages alternative data to assess clients' repayment abilities and predict which applicants are most likely to default.



## Objective
Analyze loan applicant data provided by **Home Credit** and identify applicants most likely to default using machine learning techniques.



## Steps
1. **Data Preprocessing**:
   - Automated using a separate Python file (`preprocessing_functions.py`) for reusable functions.
2. **Model Training**:
   - Trained multiple machine learning models to evaluate default risk.
3. **Model Evaluation**:
   - Assessed model performance using metrics such as accuracy, precision, recall, F1-score, and AUC.
4. **Model Tracking**:
   - Tracked experiments and results using **MLflow** for reproducibility.
5. **Comparison of Model Metrics**:
   - Selected the best model based on evaluation results.



## Tech Stack
- **Language**: Python
- **Environment**: Google Colab
- **Dataset**: can be found [here](Data/application_train.7z)



## Project Structure
1. **`preprocessing_functions.py`**:
   - Includes all necessary library imports and reusable functions.
   - Automates data preprocessing and utility functions.
2. **`Application.ipynb`**:
   - The primary notebook, importing `preprocessing_functions.py` to streamline the workflow.



## Machine Learning Techniques
The following models were trained and evaluated:
- Random Forest Classifier
- XGBoost Classifier
- CatBoost Classifier
- Logistic Regression
- Gradient Boosting
- AdaBoost Classifier
- Balanced Random Forest Classifier



## Evaluation Results
| Metric       | Best Model                |
|--------------|---------------------------|
| Accuracy     | Random Forest Classifier  |
| Precision    | Random Forest Classifier  |
| Recall       | Logistic Regression       |
| F1-Score     | CatBoost Classifier       |
| AUC          | CatBoost Classifier       |



## System Flowchart
![System Flowchart](https://github.com/user-attachments/assets/ad3d6916-7362-41e1-93a8-3d8871b94f82)



## Evaluation Metrics
![Evaluation Results](https://github.com/user-attachments/assets/bce51c51-4680-498a-8646-774f2ebc5903)
![Evaluation Results](https://github.com/user-attachments/assets/983b4672-4288-421e-bc8f-c690b06f4ddd)


