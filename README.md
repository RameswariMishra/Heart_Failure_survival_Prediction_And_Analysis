# Heart Failure Survival Prediction & Analysis

## Project Overview

This project focuses on predicting patient survival outcomes in heart failure cases using clinical and demographic variables. The goal is to leverage machine learning techniques to identify key risk factors associated with mortality and support early clinical decision-making.

The analysis combines exploratory data analysis, predictive modeling, and model evaluation to assess survival risk in heart failure patients.

## Objectives

- Analyze clinical features associated with heart failure survival

- Build and evaluate machine learning models to predict mortality risk

- Identify key predictors influencing patient outcomes

- Demonstrate end-to-end healthcare analytics workflow

## Analytical Approach

### Data Understanding & Cleaning

- Reviewed clinical variables (age, ejection fraction, serum creatinine, etc.)

- Handled missing values and data type inconsistencies

### Exploratory Data Analysis (EDA)

- Distribution analysis of clinical indicators

- Correlation analysis between features and survival outcomes

- Visualization of mortality patterns across patient subgroups

### Feature Engineering

- Selection of clinically relevant predictors

- Scaling and transformation where appropriate

### Model Development & Evaluation

- Trained multiple classification models

- Evaluated performance using accuracy and other relevant metrics

- Compared model behavior and interpretability

## Models Developed

The following machine learning models were implemented and evaluated:

- Logistic Regression – baseline interpretable model for mortality prediction

- Decision Tree Classifier – rule-based model capturing nonlinear relationships

- Random Forest Classifier – ensemble model improving predictive robustness

- Support Vector Machine (SVM) – margin-based classifier for complex decision boundaries

These models help balance interpretability and predictive performance, which is critical in healthcare applications.

## Key Insights & Findings

Clinical features such as ejection fraction, serum creatinine, and age showed strong association with survival outcomes.

Tree-based models captured nonlinear relationships more effectively than linear models.

Ensemble methods demonstrated improved stability over single estimators.

Results highlight the potential of ML models to assist clinicians in identifying high-risk patients early.

## Tools & Technologies

```
Python

Pandas, NumPy – data processing

Matplotlib, Seaborn – visualization

Scikit-learn – machine learning models & evaluation

Jupyter Notebook – analysis environment
```
## Repository Structure

```
heart-failure-survival-prediction/
│
├── notebooks/
│   └── Heart_Failure_Survival_Prediction_and_Analysis.ipynb
│
├── figures/
│   └── charts/
│
├── README.md
├── requirements.txt
└── .gitignore

```
## 🚀 How to Run the Project

### 1. Clone the repository
```
git clone https://github.com/your-username/heart-failure-survival-prediction.git
```
### 2. Install dependencies
```
pip install -r requirements.txt
```
### 3. Launch Jupyter Notebook
```
jupyter notebook
```
### 4. Open and Run
```
notebooks/Heart_Failure_Survival_Prediction_and_Analysis.ipynb
```

## Impact & Relevance

- Demonstrates healthcare-focused machine learning for clinical risk prediction.

- Highlights how data-driven models can support early intervention and patient risk stratification.

- Showcases end-to-end analytics skills relevant to healthcare analytics, biostatistics, and ML engineering roles.

- Emphasizes responsible use of predictive models in medical decision-support contexts.

## Limitations & Future Work

### Limitations

- The dataset represents a limited patient population, which may affect generalizability.

- Survival prediction is based on observational clinical data, limiting causal interpretation.

- Temporal progression of patient health indicators was not explicitly modeled.

### Future Improvements
- Incorporate larger and more diverse clinical datasets.

- Explore time-to-event (survival analysis) models such as Cox Proportional Hazards.

- Apply model explainability techniques (e.g., SHAP) to enhance clinical interpretability.

- Extend the work into a clinical decision-support dashboard for real-world use.

## Author

Created by Rameswari Mishra
