# Metals Plant Steel Temperature Prediction

## Project Description
The goal is to build a model that predicts the temperature of steel in a metallurgical plant.  
The objective is to optimize production costs by reducing electricity consumption during the steel processing stage.  
Data is indexed by batch number and extracted directly from the plant's process control system.  

## Key Findings
A comprehensive data preprocessing was performed, including the removal of outliers and missing values, feature scaling, and the creation of new features.  
Feature correlations were investigated. Features with high correlation were removed from the linear regression model to avoid multicollinearity.  
A feature influence matrix on the predictions of the chosen model was created.  

The best MAE value achieved was 6.66 using a linear regression model, satisfying the primary condition of the task: MAE < 6.8.  

## Additional Information
Toolkit: Matplotlib, Pandas, NumPy, Python, CatBoost, Scikit-learn, EDA, Data Preprocessing.
