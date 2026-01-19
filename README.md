# task-3
Exploratory Data Analysis (EDA) – Iris & Netflix Datasets
Project Overview

This project is part of the AI & ML Internship – Task 3 and focuses on performing Exploratory Data Analysis (EDA) to understand data distributions, feature behavior, and relationships using visualization techniques. Two datasets are analyzed: Iris Dataset and Netflix Movies and TV Shows Dataset.

Datasets Used:
Iris Dataset

File: Iris.csv

Description: Contains measurements of iris flowers across three species.

Key Columns:
SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm (Numerical)
Species (Categorical – Target Variable)

Insights:
Petal features show strong correlation and are more effective for species classification than sepal features. Outliers are minimal.

Netflix Movies and TV Shows Dataset

File: netflix_titles.csv

Description: Contains metadata of movies and TV shows available on Netflix.

Key Columns:
Type, Release Year, Rating, Duration, Country, Listed Genres (Categorical/Numerical)

Insights:
Movies dominate the platform, most content was added after 2015, movies are typically under 120 minutes, and content production is concentrated in a few countries.

Tools and Technologies:
Pytho
Google Colab 

Libraries: Pandas, Matplotlib

EDA Summary:
Data loading and structure inspection
Missing value analysis
Histograms for numerical features
Count plots for categorical features
Box plots for outlier detection
Correlation analysis for feature relationships

Repository Structure
├── Iris.csv
├── netflix_titles.csv
├── Untitled20.ipynb
├── Untitled21.ipynb
└── README.md

Conclusion

This EDA provided a clear understanding of both structured and real-world datasets, highlighting important features, trends, and relationships. The analysis builds a strong foundation for future machine learning and predictive modeling tasks.
