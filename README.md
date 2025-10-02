📊 Data Analysis and Visualisation – Recruitment Fairness Project

Overview
This project focuses on building a predictive and interpretable machine learning pipeline for recruitment data. Using a dataset of job applicants, the aim was to explore patterns, build classification models, and evaluate fairness to ensure ethical AI-driven hiring decisions.

Objectives

Explore applicant data through feature engineering and pattern discovery.

Build classification models to predict hiring outcomes.

Apply explainability methods (SHAP, LIME) for transparency.

Test models for fairness (group & individual metrics).

Methods & Techniques

Data Exploration: Discretisation, feature engineering (e.g., referee alignment & diversity).

Unsupervised Learning: K-Medoids clustering to uncover subgroup hiring patterns.

Association Rule Mining: Apriori algorithm for identifying hiring-related rules.

Supervised Learning:

Decision Trees

Random Forest

Bagging

AdaBoost

XGBoost (best performing, ~98% accuracy)

Explainability:

SHAP (global feature importance)

LIME (local instance-level explanations)

Fairness Testing:

Group fairness (gender, age, university background)

Individual fairness (similarity-based consistency)

Key Findings

Academic performance (A-levels) strongly influenced hiring outcomes.

Referees (quality, diversity, alignment) had measurable effects, raising fairness concerns.

XGBoost outperformed other classifiers with strong predictive accuracy and generalisation.

Fairness analysis showed high individual fairness but potential bias towards elite universities.

Tools & Libraries

Python (pandas, numpy, scikit-learn, matplotlib, seaborn)

mlxtend (association rule mining)

pyclustering (K-Medoids)

SHAP, LIME (explainability)

XGBoost

Reflections

This project demonstrates how advanced machine learning techniques can be integrated with ethical considerations such as fairness and interpretability. By combining predictive performance with fairness analysis, it offers a blueprint for responsible AI in recruitment systems.
