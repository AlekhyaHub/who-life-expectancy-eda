# WHO Life Expectancy — Data Cleaning & Exploratory Data Analysis

## Overview
This project analyzes the WHO Life Expectancy dataset (2938 records, 193 countries, 2000–2015) using Python. It covers data cleaning, missing value imputation, outlier detection, and exploratory data analysis to uncover key factors influencing life expectancy across countries.

## Tools Used
- Python (Pandas, NumPy)
- Matplotlib, Seaborn (Data Visualization)
- Jupyter Notebook

## Dataset
Source: [WHO Life Expectancy Dataset (Kaggle)](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)

## Key Steps
1. **Data Cleaning:** Handled missing values using country-wise median imputation, cleaned column names, checked for duplicates.
2. **Outlier Detection:** Used boxplots to identify and understand outliers in Life Expectancy and GDP.
3. **Exploratory Data Analysis:** Analyzed relationships between life expectancy and factors like GDP, Schooling, Development Status, and time trends using scatter plots, boxplots, and a correlation heatmap.

## Key Findings
1. **Schooling has the strongest positive correlation (0.71)** with life expectancy — stronger than GDP (0.43), suggesting education access may be as important as economic wealth for health outcomes.
2. **Adult Mortality (-0.70) and HIV/AIDS (-0.56)** show the strongest negative correlations with life expectancy.
3. **Developed countries have ~10 years higher median life expectancy** (79 years) than developing countries (69 years), with developing countries showing much wider variation.
4. **GDP correlates positively with life expectancy but non-linearly** — the relationship is strong at lower GDP levels and plateaus at higher GDP.
5. **World average life expectancy rose steadily from 66.7 (2000) to 71.6 (2015)** — a 5-year improvement over 15 years, reflecting global advances in healthcare.
6. **GDP distribution is highly unequal across countries**, with most nations clustering at lower GDP levels.

## Files
- `eda_notebook.ipynb` — Full analysis notebook (cleaning, outlier detection, EDA, visualizations)
- `Life Expectancy Data.csv` — Dataset used

## Author
Gourraju Alekhya
