# Titanic Dataset — Exploratory Data Analysis

## Project Overview

This project explores the Titanic passenger dataset using Python to understand passenger characteristics, examine data quality, and identify patterns associated with survival.

The project is part of my ongoing Data Analytics learning journey, where I practice exploratory data analysis on real-world datasets and document evidence-based findings.

## Objectives

- Understand the dataset structure and data types.
- Identify missing values and potential outliers.
- Explore numerical and categorical variables.
- Analyze survival rates across passenger classes and sex.
- Use visualizations and statistical summaries to communicate insights.

## Dataset

The Titanic dataset contains passenger information such as age, sex, passenger class, fare, and survival status.

The dataset is loaded using Seaborn's built-in Titanic dataset.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Analysis Performed

- Dataset inspection and descriptive statistics
- Missing-value analysis
- Age distribution and skewness analysis
- Box plots and IQR-based potential outlier detection
- Grouped analysis using Pandas
- Survival-rate comparisons by passenger class and sex

## Key Findings

- First-class passengers had a higher observed survival rate than second- and third-class passengers.
- Female passengers had a higher observed survival rate than male passengers across all three passenger classes.
- First-class females had the highest observed survival rate (96.81%), while third-class males had the lowest (13.54%).
- Comparing survival percentages is more informative than comparing raw survivor counts when group sizes differ.

## Conclusion

The analysis reveals differences in observed survival rates across passenger classes and sex. These findings describe associations in the dataset and do not, by themselves, establish causation.

## How to Run

1. Open `Titanic_EDA_Analysis.ipynb` in Google Colab or Jupyter Notebook.
2. Run the notebook cells in order.
3. Ensure an internet connection is available when loading the dataset through Seaborn.

## Learning Outcomes

This project helped me practice data inspection, missing-value analysis, distribution analysis, outlier detection, grouped analysis, data visualization, and communicating data-driven findings.

---

*This is a learning project and will be improved as I develop my data analysis skills.*
