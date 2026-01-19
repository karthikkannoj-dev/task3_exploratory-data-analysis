Overview

This project performs Exploratory Data Analysis (EDA) on a real-world dataset to understand data patterns, distributions, relationships, and outliers using Python visualizations.
EDA helps in understanding data before applying Machine Learning or Analytics models.

 Objectives

Understand dataset structure and features

Analyze numerical and categorical data

Detect outliers using box plots

Identify relationships using correlation heatmap

Summarize insights for decision-making

🛠️ Tools Used

Python

Pandas – data handling

Matplotlib – visualization

Seaborn – advanced charts

Jupyter Notebook

 Dataset

Netflix Movies and TV Shows Dataset

This dataset contains:

Type (Movie / TV Show)

Title, Country

Release Year

Rating

Duration

Genre

 Project Structure
EDA_Task3

── eda.ipynb
── netflix.csv
── insights_report.pdf
── README.md

 Steps Performed
1. Data Understanding

Loaded dataset using Pandas

Checked shape, data types, and missing values

2. Numerical Analysis

Used histograms to analyze distribution

Studied release year trends

3. Categorical Analysis

Used count plots for type, rating, country, and genre

4. Outlier Detection

Used box plots to detect abnormal values

5. Correlation Analysis

Created heatmap to understand feature relationships

6. Insights & Feature Selection

Identified important features for prediction

Summarized findings in simple bullet points

Key Insights

Netflix content increased rapidly after 2015

Movies are more than TV shows

USA and India produce the most content

Old movies appear as outliers

Categorical features are highly informative

 How to Run
pip install pandas matplotlib seaborn

jupyter notebook eda.ipynb

 Deliverables

EDA Notebook

Visual Insights Report

GitHub README
