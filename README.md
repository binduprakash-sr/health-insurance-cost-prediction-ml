# Health Insurance Cost Prediction using Machine Learning

## Executive Summary

This project develops a machine learning system to predict health insurance claim costs using customer demographic, lifestyle, and health-related factors such as age, BMI, smoking status, blood pressure, diabetes condition, and number of dependents.

Multiple regression models were trained and compared using MAE, RMSE, and R² Score. **Random Forest Regressor** achieved the best performance, while SHAP analysis identified smoker status, age, and BMI as the most influential factors affecting claim cost.

---

## Project Overview

Accurate health insurance cost prediction helps insurance companies estimate future claim expenses, optimize premium pricing, reduce financial risk, and improve decision-making.

The dataset contains customer information such as:

- Age  
- Gender  
- Weight  
- BMI  
- Smoking Habits  
- Blood Pressure  
- Diabetes Condition  
- Regular Exercise  
- Number of Dependents  
- Occupation  
- City  
- Hereditary Diseases  

The objective of this project is to build and evaluate multiple machine learning regression models to predict insurance claim amounts with high accuracy.

---

## Models Used

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- K-Nearest Neighbors Regressor  
- XGBoost Regressor  

---

## Best Model

**Random Forest Regressor** achieved the highest R² Score and lowest prediction error among all tested models.

---

## Explainable AI (SHAP Analysis)

SHAP (SHapley Additive exPlanations) was used to interpret model predictions.

Top influential factors affecting insurance claims:

1. Smoker Status  
2. Age  
3. BMI  
4. Number of Dependents  
5. Weight  

---

## Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- XGBoost  
- SHAP  
- Joblib  
- Jupyter Notebook  

---

## Project Workflow

1. Data Collection  
2. Data Preprocessing  
3. Missing Value Handling  
4. Exploratory Data Analysis (EDA)  
5. Feature Selection  
6. Train-Test Split  
7. Model Training  
8. Hyperparameter Tuning  
9. Performance Evaluation  
10. Model Explainability  
11. Best Model Selection  
12. Model Saving  

---

## Evaluation Metrics

- MAE (Mean Absolute Error)  
- RMSE (Root Mean Squared Error)  
- R² Score  

---

## Key Insights

- Smokers tend to have significantly higher insurance claims.  
- Higher BMI and increasing age contribute to higher claim amounts.  
- Ensemble models outperformed basic linear models.  
- Random Forest provided the most accurate and stable predictions.  

---

## Future Improvements

- Deploy as a Streamlit Web Application  
- Add real-time prediction interface  
- Use larger real-world datasets  
- Apply deep learning models for further optimization  

---

## Conclusion

This project successfully developed a machine learning solution for predicting health insurance claim costs.

Among all regression models tested, **Random Forest Regressor** performed best and was selected as the final model. SHAP explainability further improved trust and interpretability of predictions.

---

## Author

**Bindu Prakash**
