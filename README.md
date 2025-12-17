# HMI_project
2025 DSHB capstone project 
Project by : Sadaf Nasir, Peixuan Xu, and Kyoheon Hwang

## Sadaf's Contribution

### 1. Merging Datasets
(file: hmi_capstone.qmd)
- Here, I inspected individual datasets and cleaned them as necessary
to prepare for merging
- I also derived some key features prior to merging

### 2. Modeling
(file: hmi_capstone_models)
- Here, I performed EDA
- Derived some more key features
- Ran linear regression models
- Created data visualizations

### 3. Final Paper
(file: Nasir_capstone_report.pdf)
- Contains final report of capstone project

###4. Data files
(files: perceived_stress_report_new.csv &
hmi_capstone_data_wide.csv)
- Contains the specific stress dataset that was used
- As well as the final merged dataset used in analyses

### The overarching goal of this project is to explore the impact of well-being on engagement of the Healthy Minds Program application.


## Kayden's part

### 1. Data Cleaning
(file: HMI_project_summer_final.qmd)
- In this code, I omitted repetiting data and outlier
- and then concatenated five datasets into one DataFrame.
- Also, labeling and classifying activities

### 2. Regression Modeling
(file: HMI_summer_modeling_final.ipynb)
- Exploratory Data Analysis
- Visualization for univariate/multivariate distribution
- OLS regression
- Pre-Post ANCOVA (OLS)

### 3. ML Modeling
(file: HMI_KNN_RF_class_model.ipynb)
- KNN, Random Forest models for prediction of app retension (classification problem)

(file: HMI_MLP_class_model.ipynb)
- Multi-layer Perceptron modeling for prediction of app retention (classification problem)

(file: reg_model_prepost_Ancova.ipynb)
- main research objective
- KNN, Rnadom Forest, and MLP modeling for prediction of post intervention mental wellbeing (regression problem)



## Peixuan(Nancy)'s part

### Time-of-Day and Engagement in a Mobile Mindfulness App

This folder contains the final materials for a research project examining whether **time of day (morning, afternoon, evening)** predicts user engagement in a mobile mindfulness application.

### 1. `time_engagement.ipynb`
This Jupyter Notebook contains the full analytical workflow for the project, including:
- Data loading and preprocessing  
- Data cleaning and feature engineering  
- Exploratory data analysis and visualization  
- Statistical modeling using a Negative Binomial GLM  
- Model-based predictions and visualizations of engagement patterns  

This file documents all coding steps used to generate the results reported in the final paper.

### 2. `HMI_Final_Report_Peixuan(Nancy).pdf`
This PDF is the **final written report** for the project. It includes:
- Background and theoretical motivation  
- Research questions and analytic plan  
- Methods and modeling strategy  
- Results and interpretation  
- Discussion, limitations, and future directions  

The report synthesizes findings from the analyses conducted in `time_engagement.ipynb`.

### Project Overview

The goal of this project is to investigate whether **temporal patterns of practice** are associated with higher engagement in a digital mindfulness intervention, while controlling for demographic factors such as age. Engagement is operationalized using multiple metrics to ensure robustness of results.



