# Diabetes Prediction (Classification Algorithm)

## Overview
This project focuses on building and evaluating machine learning (ML) classification models to predict whether a person has diabetes based on medical and demographic features. It was developed as an introductory machine learning assignment and demonstrates an end-to-end ML workflow, from data exploration to model evaluation.

## Disclaimer
This project was completed as part of the first machine learning modeling assignment under the K-Youth Development Program. It is shared publicly for educational purposes, knowledge sharing, and portfolio demonstration.

## Project Objectives
The main goals of this project are to:

- Explore and understand the dataset through exploratory data analysis (EDA)
- Clean the data by handling missing values and outliers where appropriate
- Identify the target variable and analyze relationships between features
- Apply feature engineering techniques when necessary
- Train and compare multiple machine learning classification algorithms
- Evaluate model performance using appropriate metrics and select the best-performing model

## Datasets
The project uses two CSV files:

- `train.csv`: Training dataset used for model development
- `test.csv`: Test dataset used for model evaluation

Each record represents a patient, with medical and demographic attributes used to predict diabetes status.

## Column Description
1. **p_id**: Patient identifier
2. **no_times_pregnant**: Number of times pregnant
3. **glucose_concentration**: Plasma glucose concentration (2 hours in an oral glucose tolerance test)
4. **blood_pressure**: Diastolic blood pressure (mm Hg)
5. **skin_fold_thickness**: Triceps skin fold thickness (mm)
6. **serum_insulin**: 2-hour serum insulin (mu U/ml)
7. **bmi**: Body mass index (weight in kg / height in m²)
8. **diabetes pedigree**: Measure of genetic risk based on family history
9. **age**: Age in years
10. **diabetes**: Target variable (0 = non-diabetic, 1 = diabetic)

## Notes & Learnings
On the notebook in the first commit (2025-12-13), the instructor's feedback emphasized the importance of appropriate data handling techniques. In particular, replacing missing values with the mean or median is not recommended when a feature has nearly 50% missing data, as this can distort data distributions and negatively impact model learning.

## Skills Demonstrated
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Feature analysis and basic feature engineering
- Supervised machine learning (classification)
- Model evaluation and comparison
- Practical use of Python ML libraries (pandas, NumPy, scikit-learn)

## Intended Audience
This repository is intended for:

- Recruiters reviewing entry-level machine learning portfolios
- Students and beginners learning applied machine learning
- Anyone interested in understanding a basic diabetes classification problem