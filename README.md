# Employee Attrition Prediction 🧠

Use machine learning to predict if an employee will leave a company — made as part of the **EduSkills Google AI-ML Internship (Week 2)**.

## 📌 Problem Statement
Attrition results in crores of losses for companies every year. In this project, we make an ML model which can predict attrition based on Human Resource factors such as overtime, salary, work-life balance, etc.

## 📦 Dataset
[IBM HR Analytics Employee Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Employees: 1,470 | Features: 35 | Attrition rate: 16.1%

## ⚙️ Models used
| Model            | ROC-AUC |
| ---------------- | ------- |
| Logistic         | baseline|
| Random Forest    | ✅      |
| Gradient Boost   | ✅ Best |

## 🔍 Key Findings
- **Overtime** is the top factor that determines attrition
- Riskiest period: **First 1-2 years** of service
- Department with the highest attrition rate: **Sales** (~20.6%)
- Salary does matter, but not as much as work-life balance

## 🛠️ Libraries
`pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `numpy`
