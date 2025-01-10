# 2025 Prediction for Canada Per Capita Income

## Table of Content

- [Project Overview](#project-overview)
- [Technologies](#technologies)
- [Dataset](#dataset)
- [Plot Prediction](#plot-prediction)
- [Data Visualization](#data-visualization)

### Project Overview

<img width="704" alt="Canada Per Capita Income 2025 Prediction" src="https://github.com/user-attachments/assets/a0282af5-cff6-4495-83bd-c8d3b895e824" />

"Canada's Per Capita Income" is a measure of the average amount of money earned per person in the country.

Per Capita Income is used to evaluate the standard of living and quality of life for a population. 
It is also used to compare the wealth of different populations and to meadsure a sector's average income

This project is aimed to predict the 2025 Per Capita Income for Canadians having a single attribute/variable using Machine Learning Technique; Linear Regression for a univariate analysis, where "Per Capita Income" is a dependent variable and "Year" is an independent variable

### Technologies

- Programming Language: Python
- Libraries: NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn
- Tool: Jupyter Notebook

### Dataset

The Dataset used in this analysis is canada_per_capita_income.csv, which contains just two features; per capita income & year, which ranges from 1970-2016

### Plot Prediction

    plt.figure(figsize=(10, 5))
    
    plt.gca().set_facecolor('lightgrey')
    
    plt.xlabel('year')
    
    plt.ylabel('per capita income (US$)')
    
    plt.scatter(df['year'],df['per capita income (US$)'], color = 'red', marker = '+')
    
    plt.plot(df['year'], reg.predict(df[['year']]), color = 'blue')
    
    plt.scatter(2025, reg.predict([[2025]]), color='purple', marker='o', label='Prediction (2025)')
    
    plt.title('2025 Prediction for Canada Per Capita Income')
    
    plt.legend()

### Data Visualization

Data Viz Using Matplotlib

(See the .ipynb file for code and steps)
