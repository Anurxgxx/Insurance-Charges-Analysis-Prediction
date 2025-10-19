🩺 Insurance Charges Analysis & Prediction

A machine learning project to analyze and predict medical insurance charges using patient demographic and lifestyle data. The project uses Linear Regression and exploratory data analysis to uncover key cost drivers such as smoking status, BMI, and age.

📊 Overview

📁 Dataset: 1,338 patient records (insurance.csv)

🎯 Goal: Predict charges based on patient features

🧠 Model: Linear Regression (R² ≈ 0.865)

🔍 Key Findings: Smoking, BMI, and age significantly impact insurance costs

⚙️ Workflow

Data Analysis: Cleaned and explored 1,300+ records.

Visualization: Scatter plots, box plots, and heatmaps revealed strong correlations.

Modeling: Built and evaluated Linear Regression and regularized models.

Insights: Smoking alone increases charges by ~23,000+, with BMI and age as major contributors.

📈 Results
Model	R² Score
Linear Regression	0.865
Ridge Regression	0.865
Lasso Regression	0.849

✅ Linear Regression explains ~86% of the variance in insurance charges.

📊 Sample Visualizations

Charges vs Age: Older patients → higher charges

Charges by Smoking: Smokers → significantly higher charges

Charges vs BMI: Higher BMI, especially with smoking, increases cost

🛠️ Tech Stack

Python, pandas, numpy

matplotlib, seaborn

scikit-learn

Jupyter Notebook
