# data-analysis-plp-assignement
# Iris Dataset Analysis

## Overview

This repository contains a Jupyter Notebook that performs data analysis on the Iris dataset. The analysis includes loading the dataset, exploring its structure, cleaning the data, performing basic statistics, and visualizing the results using various plots.

## Dataset

The Iris dataset is a well-known dataset in the field of machine learning and statistics. It contains measurements of sepal length, sepal width, petal length, and petal width for three species of iris flowers.

## Tasks Completed

### Task 1: Load and Explore the Dataset

1. **Loading the Dataset**: The Iris dataset was loaded using the `pandas` library.
2. **Inspecting Data**: The first few rows of the dataset were displayed using the `.head()` method.
3. **Exploring Structure**: The structure of the dataset was explored by checking data types and identifying any missing values.
4. **Data Cleaning**: Missing values were addressed by either filling or dropping them.

### Task 2: Basic Data Analysis

1. **Basic Statistics**: Basic statistics of the numerical columns were computed using the `.describe()` method.
2. **Grouping Data**: Grouping was performed on the categorical column (species), and the mean of numerical columns was calculated for each species.
3. **Findings**: Interesting patterns and findings were identified from the analysis.

### Task 3: Data Visualization

1. **Visualizations Created**:
   - **Line Chart**: Trends over time (if applicable).
   - **Bar Chart**: Comparison of average petal length across species.
   - **Histogram**: Distribution of petal length and width.
   - **Scatter Plot**: Relationship between sepal length and petal length.

2. **Customization**: Plots were customized with titles, axis labels, and legends using `matplotlib` and `seaborn` for enhanced visual appeal.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn

## Error Handling

The code includes error handling to manage potential issues such as:
- File not found errors when loading datasets.
- Parser errors if the CSV files are unreadable.
- Handling missing data appropriately.
