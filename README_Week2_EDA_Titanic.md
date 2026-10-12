# Week 2: Exploratory Data Analysis and Visualization

**Student:** Sanitta Sibi  
**Project:** Exploratory Data Analysis (EDA) of the Titanic dataset  
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab

## Project Overview

This project explores the publicly available Titanic passenger dataset to identify patterns, relationships, and unusual observations. The notebook includes descriptive statistics, grouped comparisons, data visualizations, correlation analysis, and interpretation of findings.

## Analyses Included

- Dataset structure, data types, missing values, and duplicate checks
- Overall survival distribution
- Survival by passenger class and gender
- Combined analysis of gender and passenger class
- Age and ticket-fare distributions
- Survival by age group, family size, fare group, and embarkation town
- Passenger class composition by embarkation town
- Correlation matrix and heatmap
- Inspection of zero-fare records and highest ticket fares
- IQR-based fare outlier detection, with results compared across passenger classes
- Summary of findings, limitations, and implications for future analysis

## Dataset

The notebook loads the Titanic dataset using Seaborn's `sns.load_dataset("titanic")` function. The dataset contains passenger characteristics and survival outcomes. Because it is accessed through Seaborn, an internet connection may be required when running the notebook for the first time.

## Run the Notebook

1. Open `Week_2_EDA_Titanic.ipynb` in GitHub or download it.
2. Open [Google Colab](https://colab.research.google.com/).
3. Select **File → Upload notebook** and choose the downloaded `.ipynb` file.
4. Run the cells from top to bottom.

## Important Notes

This is an exploratory, observational analysis. Associations shown in charts and correlations do not prove causation. Missing values and small subgroup sizes may affect some comparisons. IQR-flagged fares are unusual values, not necessarily data errors, so they are investigated rather than automatically removed.
