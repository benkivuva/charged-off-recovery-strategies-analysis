# Project Name: Analyzing Recovery Strategies for Charged-off Accounts

## Project Description

The objective of this project is to determine whether the incremental amount the bank earns exceeds the additional cost of assigning customers to a higher recovery strategy. This is done by analyzing a situation where a bank has assigned delinquent customers to different recovery strategies based on the expected amount the bank believed it would recover from the customer. 

The data set used for this analysis is from a bank's charged-off accounts, which includes information on the recovery strategy assigned to each customer, their demographic data, and the amount of debt owed. The main aim is to investigate whether there is a statistically significant difference in the incremental amount earned by the bank between the different recovery strategies assigned to customers, after accounting for other factors like demographic information.

This project involves using statistical analysis techniques such as Kruskal-Wallis tests, chi-square tests, and regression modeling to answer these questions. The Kruskal-Wallis test will be used to determine whether there are statistically significant differences between the incremental amounts earned by the bank for different recovery strategies. The chi-square test will be used to investigate the relationship between different demographic variables and the assigned recovery strategy. Regression modeling will be used to control for the effects of demographic variables when analyzing the impact of recovery strategies on the incremental amount earned.

## Installation

This project requires Python 3.x and the following Python libraries installed:

- pandas
- numpy
- scipy
- statsmodels
- seaborn
- matplotlib

The project can be run using Jupyter Notebook or any other Python IDE of your choice.

## Usage

The main script for this project is `notebook.ipynb`, which contains the code for reading in the data, performing the analysis, and generating visualizations. 

To use this project, you can clone the repository to your local machine and run the `notebook.ipynb` file in Jupyter Notebook or another Python IDE. 

