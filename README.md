# Telco Customer Churn Analysis (Learning Project)

This repository contains the Jupyter Notebook (`Telco Customer Churn.ipynb`) for my analysis of customer churn in a telecom company. This project was a learning exercise focused on data analysis, visualization, and basic predictive modeling using Python.

## Overview

The primary goal of this project was to explore the factors that contribute to customer churn in the telecom industry. I aimed to gain insights into customer behavior and identify potential drivers of churn. Key questions explored include:

1.  What percentage of customers are churning versus staying?
2.  Are there churn patterns based on gender?
3.  Do certain types of services influence churn?
4.  Which services are most profitable?
5.  What features drive customer loyalty and revenue?

## Files

* `Telco Customer Churn.ipynb`:  The Jupyter Notebook containing the complete analysis, including data loading, cleaning, exploration, and [if applicable] modeling.
* `WA_Fn-UseC_-Telco-Customer-Churn.csv`: The dataset used for the analysis (if you include it directly in the repo).

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* scikit-learn (for preprocessing, splitting, and potentially basic modeling)
* shap (for model explainability)

## Key Learnings

Through this project, I gained practical experience in:

* Loading and inspecting data using Pandas.
* Handling missing values, specifically in the `TotalCharges` column.
* Converting data types for analysis (e.g., converting `TotalCharges` to numeric).
* Exploring the dataset to understand distributions and relationships between variables.
* Preparing data for modeling (e.g., label encoding, feature scaling).  *(If you performed modeling)*
* Implementing and evaluating basic classification models to predict churn. *(If you performed modeling)*
* Using SHAP values for understanding model predictions *(If you used SHAP)*

## Next Steps (Optional)

* Investigate more advanced machine learning models for improved churn prediction.
* Perform feature engineering to create new variables that might better predict churn.
* Explore techniques for addressing class imbalance in the churn data.
* Deploy a simple churn prediction application.

## Author

* Diego Eller
