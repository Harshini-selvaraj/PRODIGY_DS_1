# Population Data Distribution Visualization

This repository contains Python code to demonstrate the generation of a sample population dataset and the visualization of its key distributions, specifically age (continuous variable) and gender (categorical variable).

## Project Overview

The goal of this project is to illustrate how to:
1. Create a synthetic dataset representing a population.
2. Visualize the distribution of a categorical variable using a bar chart.
3. Visualize the distribution of a continuous variable using a histogram.

## Setup and Dependencies

To run this notebook, you will need the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install them using pip:
```bash
pip install pandas numpy matplotlib seaborn
```

## Code Description

### 1. Data Generation (`e648a6b5`)

This cell generates a sample dataset of 1000 individuals with two features: 'Age' and 'Gender'.
- **Age**: Randomly generated integers between 18 and 65.
- **Gender**: Categorical variable with 'Male', 'Female', and 'Non-binary' options, distributed with specified probabilities.

The head of the generated DataFrame is displayed to show the structure of the data.

### 2. Gender Distribution Bar Chart (`a888f82e`)

This cell creates a bar chart to visualize the distribution of the 'Gender' variable. A `seaborn.countplot` is used to show the frequency of each gender category within the sample population.

### 3. Age Distribution Histogram (`88ff0f1f`)

This cell generates a histogram for the 'Age' variable. A `seaborn.histplot` is used to display the frequency distribution of ages, along with a Kernel Density Estimate (KDE) to show the smoothed distribution curve.

## Visualizations

Upon executing the notebook, you will see two main visualizations:

1.  **Distribution of Gender in the Sample Population**:
    A bar chart showing the count of individuals for each gender category.

2.  **Distribution of Age in the Sample Population**:
    A histogram illustrating the frequency of different age groups, accompanied by a KDE curve to highlight the overall shape of the age distribution.

These visualizations help in understanding the basic characteristics of the simulated population at a glance.

