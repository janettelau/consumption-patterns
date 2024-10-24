# Global Income Disparities, Cost and Affordability of Healthy Diets, and Obesity Rates

## Getting Started

### Installation

1. Install Python on your computer
```
https://www.python.org/downloads/
```
2. Create a new environment
```
conda create -n dev python=3.10 anaconda -y
```
3. Activate the environment
```
conda activate dev
```
4. Install all the required dependencies.
```
pip install -r requirements.txt
```
5. Clone this repository to your local computer using `git clone`.

## Overview
This project aims to explore the relationship between population GDP and the cost and affordability of healthy diets, and analyze variations across different income groups.
Furthermore, it will investigate the correlation between these dietary choices and obesity across different regions. The ultimate goal is to provide insights for policymakers to promote healthier eating habits.

## Datasets
1. Global income statistics: [https://www.kaggle.com/datasets/konradb/global-income-statistics]
2. Cost and Affordability of A Healthy Diet: [https://www.fao.org/faostat/en/#data/CAHD]
3. NCD Data Portal - WHO: [https://ncdportal.org/]

## Visualizations
Plots and maps generated from the notebooks:
- Scatter Plots
- Linear Regression Plots
- Stacked Bar Charts
- Pie Charts
- Box plots
- Interactive Maps
These can be found in the `Output` folder.

## Analysis
How does the affordability of healthy diets vary by income group?
- A scatter plot that shows that as the population’s GDP increases, the percentage of the population unable to afford healthy diets decreases.
- A greater proportion of people can afford healthy diets in high-income countries.

What is the relationship between global income levels and the cost of healthy diets?
- A scatter plot shows that the spread of the cost is the greatest among upper-middle-income countries.
- The cost of healthy diets is/takes up a relatively smaller part of people’s income in high-income countries.

## Conclusion
Overall, our analysis demonstrates that income disparities significantly impact the affordability of healthy diets, with higher-income countries showing a lower percentage of populations unable to afford healthy diets and lower costs associated with these diets. However, the cost of animal-based foods remains a considerable burden for lower-income groups, particularly in low- and middle-income countries. While income is a key factor influencing dietary choices, it only has a weak correlation with obesity rates, suggesting that other factors, such as lifestyle and culture, may also influence obesity prevalence. Further research is needed to explore the broader determinants of obesity and dietary choices across income groups.
