# HealthyCity Hospitalization Risk Analysis in Python

This project analyzes public health data in Python to identify patient characteristics associated with hospitalization for seasonal respiratory illness. The work focuses on understanding the patient population, exploring hospitalization patterns across key health and behavioural variables, and highlighting factors that may be linked to higher hospitalization risk.

## Overview

HealthyCity NGO operates community clinics across five regions and wanted to understand which patient characteristics, such as age, smoking, vaccination status, and disease severity, were linked to hospitalization. The goal was to generate clearer public health insight that could support earlier identification of higher-risk patients and more targeted intervention planning.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Label Encoding
- Grouped Analysis
- Correlation Analysis
- Data Visualization

## Dataset Overview

The dataset contains patient-level public health data with variables including:

- Patient ID
- Age
- Sex
- Region
- Smoking status
- BMI
- Number of chronic conditions
- Visits last year
- Blood pressure
- Cholesterol
- Glucose
- Flu vaccination status
- Hospitalization status
- Disease severity

## Project Workflow

1. Loaded and inspected the dataset in Python to review structure, column types, and completeness.
2. Explored hospitalization patterns across patient characteristics such as smoking status, disease severity, vaccination status, and chronic conditions.
3. Visualized grouped comparisons using charts.
4. Encoded selected categorical variables to support numerical analysis.
5. Computed correlations among selected features linked to hospitalization.
6. Interpreted the findings to highlight practical public health risk factors.

## Key Insights

- Hospitalization rates were higher among smokers than non-smokers in the grouped comparison.
- Disease severity showed a strong relationship with hospitalization, with severe cases having the highest hospitalization rate.
- Vaccination status was compared against hospitalization outcomes to explore differences in hospitalization patterns.
- Hospitalized patients had a higher average number of chronic conditions than non-hospitalized patients.
- Correlation analysis suggested that chronic conditions, disease severity, and glucose level had meaningful positive relationships with hospitalization.

## Recommendations

- Prioritize patients with more severe disease presentations for closer monitoring and earlier intervention.
- Incorporate chronic condition burden into risk screening because hospitalized patients showed a higher average number of chronic conditions.
- Strengthen preventive outreach and follow-up for patients with higher-risk behavioural and clinical profiles, including smokers and patients with elevated severity levels.
- Use the identified variables as a starting point for future predictive modeling or risk scoring work to better support hospitalization prevention efforts.

## What This Project Demonstrates

This project demonstrates the ability to use Python to inspect and analyze public health data, compare hospitalization patterns across patient characteristics, create clear visualizations, encode features for analysis, and generate practical insights from health-related data.

## Project Files

- `HealthyCity_Hospitalization_Risk_Analysis.ipynb`: Main analysis notebook
- `HealthyCity_NGO_Dataset.csv`: Source dataset used in the analysis
- `HealthyCity_NGO_Project_Overview.docx`: Original project overview document
