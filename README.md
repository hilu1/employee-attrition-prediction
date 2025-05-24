# employee-attrition-prediction
A machine learning project to predict employee attrition
# Employee Attrition Prediction

This project uses machine learning to predict employee attrition using HR data.

## Project Structure

- `data/`: Dataset files
- `notebooks/`: Exploratory data analysis and model development
- `src/`: Python scripts and functions

## Dataset

# 🧠 Employee Attrition Prediction

This machine learning project predicts whether an employee is likely to leave the company based on HR data. The project applies classification techniques to assist HR departments in proactively identifying and retaining valuable talent.

---

## 🎯 Objective

To build a predictive model that identifies employees at risk of attrition using various features such as overtime, job role, income, and job satisfaction.

---

## 📁 Dataset

- **Source**: IBM HR Analytics Employee Attrition & Performance dataset
- **File**: `/data/WA_Fn-UseC_-HR-Employee-Attrition.csv`
- **Target Variable**: `Attrition` (Yes/No)

---

## 🧪 Methodology

### 1. Data Preparation
- Cleaned and transformed the `Attrition` target into binary values (`0 = No`, `1 = Yes`)
- One-hot encoded categorical variables
- Checked for class imbalance

### 2. Modeling
- **Logistic Regression** (baseline)
- **Random Forest Classifier** with:
  - Class balancing (`class_weight='balanced'`)
  - Hyperparameter tuning using **GridSearchCV**

### 3. Evaluation
- Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix
- Feature Importance Plot

---

## 📈 Results

- Best Model: Random Forest (tuned with GridSearchCV)
- Accuracy : ~87%
- **Challenge: Low recall for the minority class (`Attrition = Yes`)
- Key Predictors:
  - `OverTime`
  - `JobRole`
  - `MonthlyIncome`
  - `Age`

---

## 📊 Feature Importance (Top 10)

> A horizontal bar chart was created using `best_model.feature_importances_` to show the top 10 predictors driving attrition.

---
## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebooks
- Author
Hilena Amare Tadesse 
