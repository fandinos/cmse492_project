# cmse492_project
CMSE 492 FINAL PROJECT - MICHIGAN STATE UNIVERSITY

# The Future of AI Careers: Emerging Roles, Skill Demands, and Salary Trends

## Description


Using a global dataset of AI-related job postings, this project identifies trends in skill demand, the rise of new roles, and changes across different regions and industries. The goal is to help workers and organizations better understand the evolving AI job market—supporting professionals in learning the right skills and helping companies plan for future talent needs.

## Structure


The data folder contains all datasets, with raw holding the original data and processed storing cleaned versions. The notebooks folder includes Jupyter notebooks for data exploration and experiments, while the src folder contains the main code organized into preprocessing, modeling, and evaluation sections. The figures folder is used to store visual outputs like graphs, and the docs folder holds additional project documentation. The main directory also has a README.md explaining the project, a .gitignore to exclude unnecessary files, and a requirements.txt listing the needed dependencies.

## Setup instructions


To set up the environment, first install Python and create a virtual environment. Then, install all required dependencies using the requirements.txt file by running pip install -r requirements.txt. This ensures all necessary libraries for data processing, modeling, and visualization are available.

## Reproducing Full Pipeline

The main code will be found under the models folder. It follows some basic steps:

1.	Load the processed dataset (data/processed/).
2.	Run preprocessing and feature engineering.
3.	Train models (Linear Regression, Random Forest, Gradient Boosting).
4.	Evaluate performance across the train/val/test split.
5.	Generate interpretability visuals:
	•	Feature importance bar plots
	•	Partial dependence plots
	•	SHAP summary and force plots
6.	All figures are automatically saved in the figures/ directory.

## Summary of Findings

Gradient Boosting emerged as the strongest model, capturing nonlinear interactions between experience level, geography, and company size. Salary is most strongly influenced by seniority and region, followed by company characteristics. Clustering revealed clear workforce segments defined by experience, education, and global location.

## Limitations and Future Work

This project provides a comprehensive view of the modern AI labor market and demonstrates how machine learning can uncover structure in global talent trends. The analysis and modeling framework can be extended for workforce planning, compensation analysis, and strategic hiring.
