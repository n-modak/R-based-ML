# Overview
The purpose of this repository is to document my walkthrough of machine learning using R
 
# Assignment 5 – R-based ML
 
This repository contains a Jupyter notebook that walks through statistical analysis in R
 
## Source
 
Tutorial followed:
[https://scipy-lectures.org/packages/statistics/index.html](https://machinelearningmastery.com/machine-learning-in-r-step-by-step/)
 
## Getting Started
 
### Create the Conda Environment
 
```
conda env create -f assignment_env.yml
conda activate stats-env
```
 
### Packages included
- Python 3
- Scipy
- Pandas
- Numpy
- OS
- Seaborn
- MatPlotLib
 
## Calculations performed
Performed basic statistical analysis including group means, standard deviations, and cross-tabulations. Applied hypothesis testing (t-tests, Mann-Whitney U, Wilcoxon, chi-squared tests), computed correlations, and built linear regression models using statsmodels to explore relationships while adjusting for covariates.
 
## Notes
- Each code block from the SciPy tutorial should be placed in its own notebook cell.
- Include **detailed comments** for every code example.
- Use **markdown cells** to structure and explain each section.
- If additional Python packages are required, install them and update the `environment.yml` or `requirements.txt` file accordingly.
 
- ## License
This repository is intended for educational use only.
 
## Acknowledgments
Based on exercises from:
https://machinelearningmastery.com/machine-learning-in-r-step-by-step/
