## Health Insurance Cost Prediction Using Linear Regression

### 📘 Overview

##### This project aims to analyze and predict medical insurance costs based on key factors such as age, BMI, smoking habits, and region.
##### By using Linear Regression, we explore how each factor affects healthcare expenses and build a model to estimate future costs for individuals.

## 📊 Dataset Information File name: health_insurance.csv
##### Total Records (Rows): 1300
##### Total Features (Columns): 8
##### Shape: (1300, 8)
##### Missing Values: None
##### Duplicates: None

### Column     Name	     Type	     Description
##### age	int64	Age of the individual
gender	object	Gender of the individual (M/F)
bmi	float64	Body Mass Index (weight/height²)
bp	int64	Average blood pressure
children	int64	Number of children/dependents covered by insurance
region	object	Residential area (northeast, northwest, southeast, southwest)
smoker	object	Smoking status (smoker / non-smoker)
medical_cost	float64	Annual medical insurance cost (target variable)
