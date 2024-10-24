# Global Income Disparities, Cost and Affordability of Healthy Diets, and Obesity Rates

## Getting Started – Installation

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

## Sources
Our datasets were retrieved from:
1. [Global income statistics]([https://www.kaggle.com/datasets/konradb/global-income-statistics)
2. [Cost and Affordability of A Healthy Diet from FAOSTAT](https://www.fao.org/faostat/en/#data/CAHD)
3. [NCD (Noncommunicable-diseases) Data Portal - WHO](https://ncdportal.org/)

## Folders
- `Resources`: contains the raw data from the above sources
  - `Raw_WIDER_data.csv`: Global income statistics
  - `Cost_Affordability_healthy_Diet_Data.csv`: Cost and affordability of healthy diets data
  - `Obesity_unhealthy_diet.csv`: Obesity and unhealthy diet data
- `cleaned_files`: contains the cleaned datasets used as input files in the notebooks
  - `merged_income_diet_final.csv`: A merged dataset containing data on global income and the cost and affordability of healthy diets
  - `obesity_final.csv`: A dataset containing only obesity data among adults for this project

## Visualizations
Plots and maps generated from the Jupyter notebooks:
- `income_diet_scatter.ipynb`: Scatter Plots and Linear Regressions
- `gabriel_project_code.ipynb`: Horizontal Stacked Bar Chart
- `felipe.ipnyb`: Pie Charts and Stacked Bar Chart
- `Affordability_Obesity_sunil.ipynb`: Linear Regressions, Box plots, and Interactive Maps

The figures and a sample of the map can be found in the `Output` folder.

## Analysis
How does the affordability of healthy diets vary by income group?
- A scatter plot that shows that as the population’s GDP increases, the percentage of the population unable to afford healthy diets decreases.
- A greater proportion of people can afford healthy diets in high-income countries.
- The r² value of 0.481 indicates a moderate correlation between the two variables.

What is the relationship between global income levels and the cost of healthy diets?
- A scatter plot shows that the spread of the cost is the greatest among upper-middle-income countries.
- The cost of healthy diets takes up a relatively smaller part of people’s income in high-income countries.
- The r² value of 0.277 indicates a weak correlation between the two variables.

How do the costs of different dietary choices vary among high, middle, and low-income populations in 2017?
- A horizontal stacked bar chart where each bar shows the proportion of costs associated with various food categories.
- The cost of animal source foods accounts for a significant portion of people’s income in low-middle-income countries.
- Vegetables have a relatively small share of dietary costs in lower-income countries than other income groups.

How does a person's income level influence the types and amounts of food they typically consume?
- A pie chart which shows that the most expensive foods worldwide are those derived from animals, followed by fruits and vegetables.
- Four pie charts (one per income group) that show all the income groups spend more than 50% of their food on Animal Source and Vegetables, on the other hand, oils and starchy staples decreases.
- A stacked bar chart that illustrates the food costs by country.

Is there a significant correlation between the unaffordability of healthy diets and the prevalence of obesity rates in different countries?
- A linear regression plot which indicates no significant correlation between the unaffordability of healthy diets and the prevalence of obesity rates in different countries based on the r² value of 0.009.
- Other factors like lifestyle may also influence obesity prevalence, and further study with a more comprehensive set of variables is needed to better understand the relationship.

Is there a correlation between global income levels (represented by GDP) and obesity rates?
- The linear regression analysis yields an r² value of 0.008, indicating no significant correlation between global income levels (GDP) and obesity rates.
- Suggests that income alone is not a strong predictor of obesity.
- An interactive map to show the prevalence of obesity around the globe was plotted. Hover over each country, represented by colored dots, to view their detailed information. The size of each dot is proportional to the percentage of the population affected by obesity.

## Conclusion
Overall, our analysis demonstrates that income disparities significantly impact the affordability of healthy diets, with higher-income countries showing a lower percentage of populations unable to afford healthy diets and lower costs associated with these diets. However, the cost of animal-based foods remains a considerable burden for lower-income groups, particularly in low- and middle-income countries. While income is a key factor influencing dietary choices, it only has a weak correlation with obesity rates, suggesting that other factors, such as lifestyle and culture, may also influence obesity prevalence. Further research is needed to explore the broader determinants of obesity and dietary choices across income groups.
