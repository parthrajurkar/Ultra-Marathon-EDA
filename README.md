# Ultra-Marathon Exploratory Data Analysis

## Overview

Exploratory data analysis of a large ultra-marathon race dataset using Python, Pandas, NumPy, Matplotlib, and Seaborn.

The analysis focuses on athlete performance, age groups, race distances, and seasonal patterns in ultra-marathon races.

## Objectives

- Clean and prepare the race dataset for analysis.
- Explore athlete and race characteristics.
- Analyze performance across race distances and age groups.
- Examine seasonal patterns in athlete performance.
- Create visualizations to communicate findings.

## Dataset

The project uses the **Two Centuries of Ultra-Marathon Races** dataset.

The raw CSV file is approximately 789 MB, so it is intentionally **not included in this GitHub repository**.

If you have the dataset locally, place the CSV in the project directory using the filename expected by the notebook:

`TWO_CENTURIES_OF_UM_RACES.csv`

## Analysis Performed

- Data loading and inspection
- Column selection and removal of unnecessary fields
- Missing-value checks
- Data type conversion
- Athlete age extraction
- Athlete performance cleaning
- Duplicate checks
- Column renaming and organization
- Race month and season analysis
- Exploratory grouping and aggregation
- Performance comparison by race distance
- Age-group analysis
- Seasonal performance analysis
- Data visualization with Seaborn and Matplotlib

## Key Areas Explored

- 50 km vs. 50 mi race performance
- Male vs. female average speed
- Athlete age groups
- Race participation and performance patterns
- Seasonal differences in average speed

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
Ultra_Marathon_EDA/
│
├── Ultra_Marathon_EDA.ipynb
├── README.md
└── .gitignore
```

## Note

This repository contains the completed analysis notebook. The large raw dataset is excluded from Git tracking because of its size.
