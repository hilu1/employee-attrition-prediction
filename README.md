# employee-attrition-prediction
A machine learning project to predict employee attrition
# Employee Attrition Prediction
This project uses machine learning to predict employee attrition using HR data.
## Project Structure


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
# Employee Attrition Prediction

This project aims to predict employee attrition using machine learning techniques. The notebook demonstrates the complete process from data preparation to advanced modeling and interpretability using SHAP values.

## 📊 Project Objective

To build a classification model that predicts whether an employee will leave the company based on features such as age, income, job role, and work conditions.

## 🔄 Workflow

1. **Data Cleaning**
   - Removed missing values
   - Encoded categorical variables using OneHotEncoder and LabelEncoder
   - Scaled numerical features

2. **Exploratory Data Analysis**
   - Visualized relationships between attrition and key variables
   - Identified imbalances in the target variable

3. **Feature Engineering**
   - Selected relevant features using domain knowledge and SHAP
   - Addressed class imbalance using SMOTE

4. **Modeling**
   - Trained multiple models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting
   - Evaluated using Accuracy, Precision, Recall, F1 Score, and ROC AUC

5. **Model Explainability**
   - Used SHAP to understand the impact of each feature on predictions

## 📌 Key Features Used

- OverTime
- Monthly Income
- Job Role
- Age
- Years at Company

## 🏆 Best Model

- **Gradient Boosting Classifier**
  - Provided the best balance between performance metrics and interpretability

## 📁 Files

- `employee_attrition_model.ipynb`: Jupyter notebook with all code and analysis
- `README.md`: Project summary and documentation

## 💻 Tools & Libraries

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- imbalanced-learn
- SHAP

## 🚀 How to Run

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
