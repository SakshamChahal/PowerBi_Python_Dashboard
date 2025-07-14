# Heart Disease Risk Estimation (Python EDA + Power BI Dashboard)
## Project Objective
The goal of this project is to analyze and predict the risk of heart disease using clinical and demographic data. This model is designed to support healthcare professionals in early diagnosis and intervention. It involves:

Exploratory Data Analysis (EDA) using Python, and

Creation of an interactive Power BI dashboard for visual insights.

## Dataset Used
Public heart disease dataset (e.g., UCI Heart Disease or Kaggle dataset)

Attributes include age, gender, cholesterol, chest pain type, resting blood pressure, maximum heart rate, exercise-induced angina, and more.

## Key Questions (KPIs)
What are the most common characteristics of patients with heart disease?

How does age, sex, and chest pain type correlate with risk levels?

What features contribute most to heart disease prediction?

What percentage of patients fall into the high-risk category?

How accurately can we predict heart disease using machine learning?

What insights can be derived interactively using Power BI filters?

## Process Followed
### Python EDA & ML (Jupyter Notebooks)
Data Cleaning: Handled missing values, standardized formats

Visualization: Histograms, heatmaps, boxplots to detect patterns and outliers

Feature Engineering: Encoded categorical variables, scaled numerical data

Model Building: Trained Logistic Regression, Random Forest, and K-Nearest Neighbors

Evaluation: Used accuracy, ROC-AUC, confusion matrix, and cross-validation

## Power BI Dashboard
Created visualizations such as risk distribution, age/gender filters, and key metrics

Enabled dynamic slicers for:

Age group

Gender

Chest pain type

Resting ECG results

Embedded Python scripts for model predictions within Power BI

## Dashboard Snapshot

![photo_6316321876825197720_y](https://github.com/user-attachments/assets/cd299013-d1e0-49cc-9c55-ab7acd16b886)


## Key Insights
Patients aged 50 and above show a significantly higher risk of heart disease.

Males are slightly more prone to heart disease than females in this dataset.

Chest pain type and max heart rate are among the strongest predictors.

Random Forest achieved the best accuracy (~87%) in model evaluation.

Power BI enables real-time filtering and insights, helpful for quick diagnosis.

## Final Conclusion
The integration of data science and business intelligence provides a powerful approach to detect and visualize heart disease risks. The model can be improved with more real-world patient data and can be deployed for use in hospital dashboards or preventive health campaigns.
