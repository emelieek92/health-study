# Health Study – Data Science Project

## Project Overview

This project is an individual assignment completed as part of my Data Science education.

The purpose of this project is to analyze health study data using Python and explore factors such as age, gender, blood pressure, cholesterol levels, smoking habits, and disease prevalence.

The project is divided into two parts, focusing on statistical analysis, data visualization, and more advanced analytical methods.

## Part 1 – Exploratory Data Analysis and Statistics

- Descriptive statistics
- Data visualization
- Simulation of disease prevalence
- Confidence intervals
- Hypothesis testing
- Statistical power analysis

## Part 2 – Advanced Analysis and Data Pipeline

- Functions, modules, and object-oriented programming
- Linear algebra and regression analysis
- Advanced data analysis and visualization
- Code documentation and reusable components

## Technologies and Libraries

- **Python:** 3.14.7
- **Development environment:** Visual Studio Code and Jupyter Notebook
- **Libraries:**
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - SciPy
  - Scikit-learn

## Installation

Install the required dependencies using:

```bash
python -m pip install -r requirements.txt
```

## Project Structure

```text
health-study/
│
├── data/
│   └── health_study_dataset.csv
│
├── report_health.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## Reproducibility

To ensure reproducible results, the project uses:

- Relative file paths for loading data.
- A fixed random seed (`42`) for simulations.
- A `requirements.txt` file containing package versions.
- A Jupyter Notebook designed to run from top to bottom using **Restart & Run All**.

## Version Control

Git and GitHub are used to track changes throughout the project.

- **main:** Main repository branch
- **del1:** Part 1 – Exploratory Data Analysis and Statistics
- **del2:** Part 2 – Advanced Analysis and Data Pipeline

## Dataset

The dataset contains health-related information, including age, sex, height, weight, systolic blood pressure, cholesterol levels, smoking status, and disease status.