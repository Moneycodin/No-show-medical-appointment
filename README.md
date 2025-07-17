# No-show-medical-appointment

# Predicting No-Show Appointments in Healthcare

This project analyzes a real-world dataset from the Brazilian healthcare system to identify key factors associated with patients not showing up for their scheduled medical appointments. The insights derived here are highly relevant to improving healthcare efficiency, particularly in the **Long Term Post Acute Care (LTPAC)** domain.

## 🎯 Objective

Design and implement an end-to-end research study to:
- Identify predictors of patient no-shows.
- Develop a machine learning model to classify likely no-show patients.
- Suggest interventions that could reduce appointment absenteeism.

## 🧠 Research Methodology

- **Hypothesis**: Factors like SMS reminders, age, medical history, and lead time influence no-show behavior.
- **Dataset**: [Kaggle - No Show Appointments](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
- **Design**:
  - Data exploration and visualization.
  - Feature engineering and class balancing.
  - Model training and evaluation (Logistic Regression, Random Forest, XGBoost).
- **Tools**: Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook.

## 📈 Results

- Best Model: **Random Forest**
- Accuracy: 82.6%
- Key Predictors:
  - Lack of SMS reminders.
  - High waiting time (lead time).
  - Specific health conditions (e.g., diabetes).
  - Age brackets (18–30 and >60).


