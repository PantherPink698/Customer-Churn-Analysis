Customer Churn Analysis — Exploratory Data Analysis
Overview

Customer churn poses a significant challenge for subscription-based businesses.
This project performs Exploratory Data Analysis (EDA) to examine customer behavior patterns associated with churn and to extract actionable insights before any predictive modeling.

This repository represents Phase 1 of a larger churn prediction workflow.
Dataset

Records: 64,374 customers

Target Variable: Churn (0 = Retained, 1 = Churned)

Missing Values: None

Features

Numerical

Age

Tenure

Usage Frequency

Support Calls

Payment Delay

Total Spend

Last Interaction

Categorical

Gender

Subscription Type

Contract Length

Objectives

Understand customer behavioral patterns

Compare churned vs retained customers

Identify features associated with churn risk

Establish a strong analytical foundation for modeling

Analysis Summary
Numerical Behaviour

Churned customers demonstrate lower usage frequency, indicating reduced engagement.

Support calls and payment delays are substantially higher among churned customers.

Retained customers show higher average total spend, highlighting revenue impact.

Age and last interaction show minimal influence on churn behavior.

Tenure exhibits a non-linear relationship with churn.

Categorical Behaviour

Churn rates vary notably across contract lengths, with shorter contracts showing higher churn.

Certain subscription types are more prone to churn.

Gender shows minimal variation in churn rates.

Visualizations

Key visualizations include:

Distribution and boxplot analysis of numerical features

Median and interquartile range (IQR) comparisons

Churn rate bar charts across categorical variables

All plots are designed to highlight behavioral differences rather than raw counts.

Tools Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

Repository Structure
customer-churn-analysis/
├── notebooks/
│   └── churn_eda_phase1.ipynb
├── images/
│   └── churn_visualizations.png
├── README.md

Next Steps

Feature engineering and encoding

Train–validation split

Churn prediction modeling

Model evaluation and business interpretation

Author

Panther Pink
Data Science & AI
Python • Machine Learning • Analytics



Link GitHub in Instagram bio

You’re doing everything right — this confusion is part of the process.
