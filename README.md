# Job Salary Prediction using Machine Learning

## Project Overview
This project involves building a machine learning pipeline to predict job salaries based on professional features. The study compares multiple regression algorithms to find the most accurate model for this specific dataset.

## Dataset and Sampling
* **Scale:** The original dataset consists of over 250,000 records.
* **Methodology:** A representative sample of 10,000 records was used for training and hyperparameter tuning. This was done to maintain computational efficiency while ensuring the model's logic remains scalable for the full dataset.

## Data Preprocessing
* **Outlier Removal:** Used the Interquartile Range (IQR) method to clean the data and improve model stability.
* **Categorical Encoding:** Converted non-numerical features into a format suitable for machine learning models.

## Model Evaluation & Results
Three models were tested using Mean Absolute Error (MAE) and R-Squared (R²) scores. 

| Model | MAE | R² Score |
| :--- | :--- | :--- |
| **Random Forest** | **9,856.71** | **0.8784** |
| SVM (SVR) | 19,605.76 | 0.5287 |
| KNN | 20,273.60 | 0.5066 |

## Conclusion
The Random Forest model performed best, explaining approximately 88% of the variance in salary data. The significantly lower MAE compared to KNN and SVM indicates that Random Forest is much better at handling the underlying patterns in this dataset.

## Tech Stack
* **Python:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn.
* **Core Skills:** Data Cleaning, Feature Engineering, Regression Analysis.
