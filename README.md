# 🧠 Employee Well-being through AI  
**A Machine Learning Approach to Analyzing Feedback and Predicting Outcomes**

---

## 🎓 Master's Thesis Project

This repository contains the code, data pipeline, and modeling framework developed for my Master's thesis at TSI. The project explores how artificial intelligence can be used to analyze employee feedback and predict well-being metrics using ethical and explainable machine learning techniques.

---

## 📌 Background & Motivation

Modern organizations collect a variety of structured and unstructured data from employees — from satisfaction ratings to open-ended survey responses. However, traditional HR analytics methods struggle to extract actionable insights from such complex datasets.

With the rise of AI and Natural Language Processing (NLP), there's an opportunity to go beyond static dashboards and use predictive models to understand drivers of employee well-being. This project addresses that opportunity while carefully considering the risks posed by deploying AI in high-stakes domains like HR.

---

## 🎯 Objectives

- Combine structured (e.g., job role, ratings) and unstructured (e.g., free-text feedback) data sources.
- Train interpretable machine learning models to predict employee satisfaction, engagement, and recommendation.
- Provide HR-friendly insights while complying with GDPR and EU AI Act guidelines.

---

## 🧮 Data & Features

A pilot survey of 50 employees was conducted using questions inspired by Gallup Q12 and extended to include:

- Stressors, management quality, communication methods
- Categorical data: Department, gender, job role
- Ordinal ratings: Satisfaction, recommendation
- Free-text comments

---

## 🛠️ Project Structure

employee-wellbeing-ai/
- ├── 📂 data/               → Raw and processed datasets (avalaible by request for caution)
- │   ├── raw/
- │   └── processed/
- ├── 📓 notebooks/          → Jupyter/Colab notebooks for EDA, modeling, evaluation
- ├── 🧩 src/                → Python modules (preprocessing, modeling, utils)
- ├── 📊 reports/            → Visualizations and model output
- ├── 📄 requirements.txt    → Python package dependencies
- ├── 📘 README.md           → Project overview and instructions
- └── 🔒 LICENSE             → Open source license

---

## 🤖 Models Used
Classification Tasks:
- Logistic Regression
- Decision Tree Classifier
- XGBoost

Regression Tasks:
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

Evaluation Metrics:
- Accuracy, Precision, Recall, F1
- R², MAE, RMSE
- Cross-Validation

Explainability:
- Feature Importance
- SHAP values
- Decision tree paths

---

## 🔐 Ethical & Legal Compliance
-  Data anonymized and collected with consent
- In line with GDPR and EU AI Act (HR use = high-risk)
- Transparent modeling with interpretable AI
- Bias audits outlined for future scaling

---

## 💡 Key Results
- Logistic Regression reached ~76% accuracy predicting employee recommendation.
- Sentiment analysis of open feedback showed moderate correlation with satisfaction.
- Supervisor support and workload emerged as top predictors in feature importance.

---

## 🚀 Getting Started
1. Clone the Repository:
- git clone https://github.com/yourusername/employee-wellbeing-ai.git
cd employee-wellbeing-ai
2. Install Dependencies:
- pip install -r requirements.txt
3. Run Notebooks:
Open notebooks from the /notebooks folder and run them sequentially:
 - 01_data_exploration.ipynb
 - 02_modeling.ipynb
 - 03_evaluation.ipynb

---
## 🗂️📁 Project management
- Got to -> https://majestic-talos-016.notion.site/master-thesis-st83814 (need create account) 
load example reuse it
- Preview of Master Thesis project management .pdf format available here -> https://studentstsi-my.sharepoint.com/:f:/g/personal/st83814_students_tsi_lv/EuwoYSAt6upDgTbYVbYt49MBeHwKpq0Lqq7pA91cm0znXQ?e=95lC0z

---

## 📚 References
- Gallup Q12 Framework
- EU Artificial Intelligence Act
- SHAP: Lundberg & Lee (2017)
- Dataset inspired by Koluit HR Dataset (Kaggle)

---

## 🧠 Author
Vija Niedre
Master’s in Computer Science, Specializing in Data Analytics & AI
📧 st83814@students.tsi.lv
🔗 [[LinkedIn or personal website](https://www.linkedin.com/in/vijaniedre/)]

---

## 📄 License
This project is licensed under the MIT License — see the LICENSE file for details.
