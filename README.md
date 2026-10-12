# Week 2 - Exploratory Data Analysis and Visualization

**Student:** Sanitta Sibi  
**Internship:** Virtual Data Science with Python Trainee  
**Task:** Week 2 - Exploratory Data Analysis and Visualization

## Project Overview

This project explores the publicly available Titanic passenger dataset using Python. The purpose is to identify patterns, relationships, and unusual observations through exploratory data analysis (EDA).

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Analysis Performed

1. Dataset exploration and descriptive statistics
2. Missing-value and duplicate-record checks
3. Survival analysis by passenger class and gender
4. Age distribution and survival analysis
5. Family-size analysis
6. Ticket-fare distribution and comparison
7. Survival analysis by embarkation town
8. Correlation matrix and heatmap
9. IQR-based fare outlier investigation
10. Summary of findings and limitations

## Key Findings

- The dataset contains 891 passenger records and 15 columns.
- The overall survival rate was 38.38%.
- First-class passengers had a survival rate of 62.96%, compared with 24.24% for third-class passengers.
- Female passengers had a higher observed survival rate than male passengers.
- Ticket fares were strongly right-skewed.
- The IQR method flagged 116 fare observations as potential outliers. These were investigated rather than automatically removed.

## Project Files

- `Week_2_EDA_Titanic.ipynb` — Google Colab notebook containing the Python code, analyses, and visualizations.

## Conclusion

This project demonstrates the use of exploratory data analysis to understand data distributions, compare passenger groups, investigate correlations, and interpret unusual observations. The findings describe associations in the dataset and do not establish causation.
