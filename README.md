# Diabetes Prediction (Classification Algorithm)

## Overview
This project focuses on building and evaluating machine learning (ML) classification models to predict whether a person has diabetes based on medical and demographic features. It was developed as an introductory machine learning assignment and demonstrates an end-to-end ML workflow, from data exploration to model evaluation.

## Disclaimer
This project was completed as part of the first machine learning modeling assignment under the K-Youth Development Program 2025. It is shared publicly for educational purposes, knowledge sharing, and portfolio demonstration.

## Project Objectives
The main goals of this project are to:

- Explore and understand the dataset through exploratory data analysis (EDA)
- Clean the data by handling invalid values and outliers where appropriate
- Identify the target variable and analyze relationships between features
- Apply feature engineering techniques when necessary
- Train and compare multiple machine learning classification algorithms
- Evaluate model performance using appropriate metrics and select the best-performing model

## Datasets
The project uses two CSV files:

- `train.csv`: Training dataset used for model development
- `test.csv`: Test dataset used for model evaluation

Each record represents a patient, with medical and demographic attributes used to predict diabetes status. The datasets are likely modified from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

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
On the notebook in the first commit (2025-12-13), the instructor's feedback emphasized that replacing invalid/missing values with the mean or median is not recommended when a feature has nearly 50% invalid/missing data, as this can distort data distributions and negatively impact model learning.

This was fixed subsequently by dropping columns with high invalid data, and imputing the rest (<10% invalid data) with median. 

## Skills Demonstrated
- Data inspection and cleaning
- Exploratory data analysis (EDA)
- Feature engineering
- Building and evaluation of supervised machine learning (classification) models 
- Practical use of Python ML libraries (pandas, numpy, matplotlib, seaborn, scikit-learn)

## Intended Audience
This repository is intended for:

- Recruiters reviewing entry-level machine learning portfolios
- Students and beginners learning applied machine learning
- Anyone interested in understanding a basic classification problem