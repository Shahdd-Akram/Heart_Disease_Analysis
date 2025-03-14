Heart Disease Dataset Analysis

Overview

This project explores the Heart Disease Dataset to uncover patterns and insights using NumPy, Pandas, Matplotlib, and Seaborn. It focuses on cleaning data, analyzing key health indicators, and visualizing trends.

What We Did

Cleaned the Data: Removed outliers using the IQR method.

Analyzed Key Metrics:

Cholesterol levels (Mean, Median, Std Dev)

Blood Pressure differences (with vs. without heart disease)

Maximum & Minimum Heart Rate

Filtered & Sorted Data:

Found patients with cholesterol > 300 mg/dL

Identified older patients (60+) with abnormal ECG

Reshaped & Split Data using NumPy.

Created Visualizations:

Histogram: Cholesterol distribution

Scatter Plot: Age vs. Max Heart Rate

Bar Chart: Heart Disease vs. No Heart Disease

3D Plot: Cholesterol, Age & Heart Disease

Pie Chart: Chest Pain Type breakdown

How to Use

Load the dataset into Pandas.

Run the outlier removal function to clean it.

Perform statistical analysis.

Call visualize_heart_disease(df) to generate insights visually.

Next Steps

Explore correlations between different health indicators.

Implement machine learning models for heart disease prediction.

This project provides a strong starting point for understanding heart disease trends and can be extended for deeper analysis!
