# Adult-Income-Analysis

This repository contains the analysis and visualizations performed on a dataset. The goal was to explore relationships between various features such as age, hours worked per week, capital gain/loss, education level, and income. A series of statistical plots and visualizations were created to uncover insights and trends within the data.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Analysis and Visualizations](#analysis-and-visualizations)
    - [Univariate Distributions](#univariate-distributions)
    - [Pairplot Analysis](#pairplot-analysis)
    - [Income Distributions by Gender and Education](#income-distributions-by-gender-and-education)
    - [Correlation Heatmap](#correlation-heatmap)
4. [Key Insights](#key-insights)
5. [Technologies Used](#technologies-used)

## Project Overview

The purpose of this project was to analyze a dataset that contains demographic and economic information, including features such as **age**, **hours worked per week**, **capital gain**, **capital loss**, **education**, and **income**. The objective was to use a variety of statistical visualizations to uncover meaningful patterns, such as income distribution by gender and education level, the relationship between hours worked and capital gains, and the correlation between multiple features.

## Dataset

The dataset used for this analysis includes the following columns:
- **age**: Age of individuals.
- **hours.per.week**: Number of hours worked per week.
- **capital.gain**: Capital gain from investments.
- **capital.loss**: Capital loss from investments.
- **education**: Education level of individuals.
- **income**: Income class (<=50K or >50K).
- **sex**: Gender of individuals.
- **workclass**: Type of employment.
- **native.country**: Country of origin.

The dataset contains both continuous and categorical features, providing a diverse range of information to analyze.

## Analysis and Visualizations

### Univariate Distributions

- **Histograms** and **Kernel Density Estimation (KDE)** plots were used to understand the distribution of key features such as age, hours worked per week, capital gain/loss, and education number.
- These visualizations highlighted skewness in several features, such as age (right-skewed) and hours worked per week (also right-skewed, with a concentration around 40 hours).

### Pairplot Analysis

- A **Pairplot** was generated to visualize pairwise relationships between the numerical features (age, hours worked per week, capital gain, capital loss, and education number).
- The **diagonal histograms** provided insights into the distribution of each feature.
- The **scatter plots** between feature pairs allowed for the observation of relationships, such as the correlation between **age and capital gain** (positive correlation) and **income levels**.
- Scatter plots also revealed that **capital gain** was higher for individuals with greater income, and that **younger people** might work **fewer hours** compared to older individuals.

### Income Distributions by Gender and Education

- A **stacked bar chart** was created to compare income distribution by gender within different **education levels**.
- The visualization showed that **males** were more likely to have **higher income** across different education levels, although the gap became more pronounced with higher levels of education.
  
### Correlation Heatmap

- A **correlation matrix** was computed to evaluate the relationships between several numerical features.
- The heatmap revealed strong correlations between **capital gain** and **income**, and weaker correlations between **hours worked per week** and other features.

## Key Insights

1. **Income and Education**: Higher levels of educat
