Exploratory Data Analysis (EDA) – Iris Dataset
Project Overview:
This project is completed as part of the AI & ML Internship – Task 3, which focuses on performing Exploratory Data Analysis (EDA) to understand data structure, feature behavior, and relationships using visualization techniques. The Iris dataset is used to analyze numerical features and identify patterns useful for prediction.

Dataset Description:
Dataset Name: Iris Dataset
File: Iris.csv
The dataset contains measurements of iris flowers belonging to three species.

Columns:
SepalLengthCm – Numerical
SepalWidthCm – Numerical
PetalLengthCm – Numerical
PetalWidthCm – Numerical
Species – Categorical (Target Variable)

Tools and Technologies:
Python
Google Colab

Libraries Used:
Pandas
Matplotlib

EDA Process:
Loaded the dataset and inspected basic information such as shape, columns, and data types.
Checked for missing values and verified data consistency.
Analyzed numerical features using histograms to understand distributions.
Analyzed the categorical feature using count plots.
Used box plots to detect potential outliers in numerical columns.
Created a correlation heatmap to study relationships among features.

Key Insights:
Petal length and petal width show strong correlation with each other.
Petal features are more effective than sepal features for distinguishing species.
Numerical features show clear distribution patterns across species.
Mild outliers are present but do not significantly affect overall analysis.

Target Variable
Species
Input Features
SepalLengthCm
SepalWidthCm
PetalLengthCm
PetalWidthCm

Repository Structure
├── Iris.csv
├── Untitled20.ipynb
└── README.md

Conclusion:

This EDA helped in understanding the dataset structure, identifying important features, and visualizing relationships between variables. The analysis provides a strong foundation for applying machine learning models in future tasks.