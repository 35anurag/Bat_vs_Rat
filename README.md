Rat vs Bat Foraging Behaviour — Assignment 3 (HIT140 Foundations of Data Science)
> Overview

This project investigates the foraging behaviours of bats and rats based on experimental data collected under controlled environmental conditions. The analysis focuses on identifying patterns and differences in arrival times, landing behaviour, and risk-taking tendencies between the two species.

The study applies data science techniques to explore hypotheses related to predator-prey interactions, food competition, and environmental influences.

> Objectives

Analyse the foraging patterns of bats and rats using structured datasets.

Compare behavioural differences between the two species.

Apply data cleaning, transformation, and statistical methods using Python.

Interpret results through data visualization and logistic regression analysis.

Present key insights with academic and ethical integrity for HIT140 submission.

> Dataset Description

Dataset name: foraging_data.csv

Variables include:

- species – Bat or Rat

- time_bin – Observation time intervals

- risk_taking_rate – Probability or frequency of risk-taking behaviour

- seconds_since_rat_arrival – Delay between arrivals

- hit_code – Binary or categorical indicator of landing success

Data source: Provided by HIT140 unit coordinators (.csv) file

> Data Analysis Approach

Key steps performed in this project:

Data Cleaning & Preparation

- Handle missing values and remove invalid records.

- Normalize and encode categorical data.

Exploratory Data Analysis (EDA)

- Use matplotlib and seaborn to visualize relationships.

- Identify patterns between risk-taking and arrival times.

Statistical Analysis

- Compute mean risk-taking rates by species and time bin.

- Use correlation and distribution analysis.

Model Development

- Apply Logistic Regression to predict species behaviour.

- Evaluate model accuracy and ROC curve.

Interpretation & Reporting

- Summarize findings with clear visual and statistical evidence.

> Tools & Technologies

Programming Language: Python 3.x

> Libraries Used:

pandas – Data cleaning and manipulation

matplotlib & seaborn – Data visualization

numpy – Numerical computation

scikit-learn – Logistic regression and metrics

> Results Summary

Bats tend to take higher foraging risks earlier in time bins compared to rats.

Rats exhibit more consistent and cautious behaviour over time.

> Output:
- Investigation A
<img width="3200" height="1530" alt="Figure_1" src="https://github.com/user-attachments/assets/8adb98ea-73d6-4fc8-adf0-9dde760d3eba" />

- Investigation B
<img width="1280" height="612" alt="Figure_2" src="https://github.com/user-attachments/assets/40ff5bb1-8a8b-4723-80cf-50133d80983d" />


