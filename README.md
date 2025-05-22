# 🧠 Employee Well-being through AI  
**A Machine Learning Approach to Analyzing Feedback and Predicting Outcomes**

---

## 🎓 Master's Thesis Project

This repository contains the code, data pipeline, and modeling framework developed for my Master's thesis at [Your University Name]. The project explores how artificial intelligence can be used to analyze employee feedback and predict well-being metrics using ethical and explainable machine learning techniques.

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

```bash
employee-wellbeing-ai/
├── data/               # Raw and processed data (anonymized)
├── notebooks/          # Colab/Jupyter notebooks for exploration & modeling
├── src/                # Python scripts for preprocessing, modeling, explainability
├── reports/            # Visualizations, SHAP plots, evaluation results
├── requirements.txt    # Python dependencies
├── README.md           # Project overview
└── LICENSE
