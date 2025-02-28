# DAI-101-ASSIGNMENT
# Iris Dataset Analysis

## Overview
This project performs an in-depth exploratory analysis of the well-known Iris dataset using Python. The analysis includes both univariate and multivariate techniques to understand the relationships between different features and species classification.

## Dataset
The dataset consists of 150 samples of iris flowers, categorized into three species:
- **Setosa**
- **Versicolor**
- **Virginica**

Each sample contains four measured attributes:
- **Sepal Length (cm)**: The length of the sepal
- **Sepal Width (cm)**: The width of the sepal
- **Petal Length (cm)**: The length of the petal
- **Petal Width (cm)**: The width of the petal

## Analysis Steps
### 1. **Univariate Analysis**
- Summary statistics to understand feature distributions
- Histograms for visualizing feature distributions
- Boxplots to examine outliers and spread

### 2. **Multivariate Analysis**
- Pairplot visualization to analyze relationships between features
- Correlation heatmap to detect feature dependencies
- Violin plots for detailed distribution analysis

## Key Findings
- **Petal length and petal width are strong indicators of species classification**, as they show clear separations between species.
- **Sepal width has overlapping distributions**, making it less useful for classification.
- **Strong correlation exists between petal length and petal width**, suggesting redundancy in classification.
- **Setosa is easily distinguishable**, whereas Versicolor and Virginica show some overlap in feature distributions.

## Dependencies
To execute the analysis, install the required libraries:
```
pip install pandas seaborn matplotlib scikit-learn
```


## Author
**ALOK KUMAR (23123003)** 
This analysis was conducted as part of an exploratory data analysis project for academic purposes.



