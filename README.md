# Probability-Distributions

## Overview
This project analyzes the Adult Income Dataset to understand the relationships between demographic factors and income levels. The analysis focuses on calculating conditional probabilities, exploring distributions of continuous variables, and visualizing key insights through various charts and graphs.

## Dataset
The Adult Income Dataset contains demographic information from U.S. Census, with the goal of predicting whether a person's income exceeds $50K/year.[https://archive.ics.uci.edu/dataset/2/adult]

## Key Variables:
Target: income (binary: >50K or <=50K)

Continuous: age, education-num, hours-per-week

Categorical: workclass, education, marital-status, occupation, relationship, race, sex, native-country

## Analysis Objectives
Calculate conditional probabilities of high income across various demographic factors

Explore distributions of continuous variables and test for normality

Visualize relationships between variables and income probabilities

Identify key factors associated with higher income levels

Demonstrate statistical concepts like the Central Limit Theorem

## Methodology
### Data Preprocessing
Handled missing values (marked as '?') using mode for categorical and median for numerical variables

Created binary high_income flag (1 if income >50K, 0 otherwise)

Binned continuous variables (age and hours-per-week) into meaningful categories

### Probability Calculations
Computed conditional probabilities P(high income | demographic factor)

Analyzed relationships across education levels, work classes, age groups, marital status, occupations, and more

### Distribution Analysis
Tested continuous variables for normality

Calculated expected values and variances

Compared observed distributions with theoretical normal distributions

### Visualizations
Created comprehensive visualizations including:

Histograms with normal distribution overlays

Box plots for continuous variables

Bar charts for categorical probability analysis

### Correlation heatmaps

Distribution comparisons across income groups

### Central Limit Theorem demonstration

## Key Findings
Education Impact
Advanced degrees (Prof-school, Doctorate) show the highest probability of high income 

High school graduates have significantly lower probability

Age Patterns
Income probability peaks in the 46-55 age group 

Declines significantly after retirement age 

Work Hours
Full-time workers (40 hours/week) have moderate income probability 

Gender Disparity
Males show significantly higher probability of high income compared to females

Occupation Differences
Executive-managerial and professional-specialty occupations show highest income probabilities

## How to Run the Code
Prerequisites
Python 3.7+

Required libraries: pandas, numpy, matplotlib, seaborn, scipy

## Installation
bash
pip install pandas numpy matplotlib seaborn scipy
Execution
Run the complete analysis script:

bash
python adult_income_analysis.py

## Code Structure
The analysis is organized into these main sections:

Data loading and preprocessing

Conditional probability calculations

Distribution analysis and normality testing

Comprehensive visualizations

Insights and interpretation

## Dependencies
pandas: Data manipulation and analysis

numpy: Numerical computations

matplotlib: Basic plotting

seaborn: Advanced statistical visualizations

scipy: Statistical tests and distribution fitting