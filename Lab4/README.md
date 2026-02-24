House Price Data Quality & Preprocessing Lab

This project focuses on the foundational steps of the machine learning pipeline: Data Quality Assessment and Preprocessing. Using a House Price Prediction dataset, the lab demonstrates how to transform raw data into a clean, normalized format suitable for predictive modeling.
# Key Tasks Performed

   Task 1: Data Quality Audit – Inspected the dataset for missing values, duplicates, and inconsistent data types.
   Task 2: Imputation Strategy – Implemented a median-based imputation strategy to handle potential missing values in numerical features (e.g., Price, Area).
   Task 3: Outlier Management – Used the Interquartile Range (IQR) method to detect and handle extreme values that could skew model performance.
   Task 4: Feature Scaling – Applied Min-Max Scaling and Z-score Standardization to ensure all numerical features (Area, Price, YearBuilt) are on a comparable scale.
   Task 5: Dimensionality Reduction (PCA) – Performed Principal Component Analysis to identify the most significant variance in the data and project high-dimensional features into a 2D space.

# Dataset Overview

The dataset contains 2,000 records of house sales with features including:

 Numerical: Area, Bedrooms, Bathrooms, Floors, YearBuilt, and Price.
 Categorical: Location (Urban, Suburban, etc.), Condition, and Garage availability.
