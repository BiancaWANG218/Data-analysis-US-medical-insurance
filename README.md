# U.S. Medical Insurance Costs

## Goal of the Project
- Understand factors affecting the price of health insurance

## Project Scope
- Exploratory data analysis and data visualization
- Understanding the relationship between insurance cost and other factors through linear regression

## An Explanation for the Factors in the Dataset
- **age:** age of primary beneficiary
- **sex:** insurance contractor gender, female, male
- **bmi:** Body mass index, providing an understanding of body weights that are relatively high or low relative to height, objective index of body weight (kg / m²) using the ratio of height to weight, ideally 18.5 to 24.9
  - overweight is a BMI greater than or equal to 25
  - obesity is a BMI greater than or equal to 30
- **children:** Number of children covered by health insurance / Number of dependents
- **smoker:** Smoking status
- **region:** the beneficiary's residential area in the US, categorized as northeast, southeast, southwest, northwest

## Data
The data used in this project includes various factors such as age, sex, BMI, number of children, smoking status, and region to analyze their impact on the cost of health insurance. Ensure you have the required data files in the appropriate directory before running the notebook.

## Visualization
The notebook includes visualizations that help in understanding the relationship between insurance costs and other factors. These visualizations are essential for comparing and interpreting the analysis results.

## Reflection
The notebook may contain sections where updates and reflections based on feedback are documented. This is crucial for understanding the iterative improvements made to the project.

## Getting Started

To get started with this project, you'll need to have the following libraries installed:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
