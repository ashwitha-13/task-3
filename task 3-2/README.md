Exploratory Data Analysis (EDA) – Netflix Movies and TV Shows Dataset
Project Overview:
This project is completed as part of the AI & ML Internship – Task 3, which focuses on performing Exploratory Data Analysis (EDA) to understand data patterns, distributions, and feature behavior using visualizations. The Netflix Movies and TV Shows dataset is analyzed to gain insights into content types, release trends, ratings, and durations.

Dataset Description:
Dataset Name: Netflix Movies and TV Shows
File: netflix_titles.csv

The dataset contains information about movies and TV shows available on Netflix, including metadata such as release year, rating, duration, and country.

Columns:
show_id – Categorical (Identifier)
type – Categorical (Movie / TV Show)
title – Categorical
director – Categorical
cast – Categorical
country – Categorical
date_added – Date
release_year – Numerical
rating – Categorical
duration – Categorical
listed_in – Categorical (Genres)
description – Text

Tools and Technologies:
Python
Google Colab 

Libraries Used:
Pandas
Matplotlib

EDA Process:
Loaded the dataset and reviewed its structure, shape, and data types.
Checked for missing values and analyzed null value distribution.
Analyzed categorical features such as content type, rating, and country using count plots.
Analyzed numerical features like release year using histograms.
Examined duration patterns separately for movies and TV shows.
Visualized trends in content addition over time.

Key Insights:
Movies form a larger portion of Netflix content compared to TV shows.
Most content was added after 2015, showing rapid platform growth.
TV shows typically have multiple seasons, while movies are mostly under 120 minutes.
Certain ratings dominate the platform, indicating target audience preferences.
Content production is concentrated in a few countries.

Target Variable:
Not explicitly defined (EDA-focused analysis)

Input Features:
Type
Release Year
Rating
Duration
Country
Listed Genres

Repository Structure
├── netflix_titles.csv
├── Untitled21.ipynb
└── README.md

Conclusion

This EDA provided a clear understanding of Netflix content distribution, trends over time, and important categorical patterns. The analysis helps identify features that can be useful for recommendation systems and predictive modeling in future tasks.