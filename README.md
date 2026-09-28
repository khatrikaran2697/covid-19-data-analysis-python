# COVID-19 Data Analysis Using Python

## Overview

An end-to-end Python data analysis project using COVID-19 confirmed
cases, deaths, and recovered-case data.

The project focuses on data cleaning, exploratory data analysis (EDA),
time-series analysis, data transformation, dataset merging, rate
calculations, and visualization.

## Objectives

-   Load and inspect multiple COVID-19 datasets.
-   Understand dataset structure, dimensions, and data types.
-   Identify and handle missing values.
-   Analyze confirmed cases across countries and over time.
-   Analyze peak daily new cases for selected countries.
-   Compare recovery rates for selected countries.
-   Analyze death-rate distributions.
-   Transform data from wide format to long format.
-   Merge confirmed, death, and recovery datasets.
-   Produce monthly country-level analysis.
-   Analyze COVID-19 trends for selected countries.
-   Create visualizations to communicate findings.

## Dataset

The provided case-study dataset contains three Excel sheets:

1.  `covid_19_confirmed_v1`
2.  `covid_19_deaths_v1`
3.  `covid_19_recovered_v1`

The case-study brief describes daily cumulative data from January 22,
2020 to May 29, 2021 and more than 276 geographic entries.

> If you redistribute the Excel file publicly, verify that you have
> permission to redistribute the dataset and add the original dataset
> source/attribution here.

## Technologies

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook

## Key Analysis Areas

### Data Cleaning

-   Date-column standardization
-   Missing-value detection
-   Forward-fill handling for time-series values
-   Province/state value standardization

### Exploratory Data Analysis

-   Country-level confirmed cases
-   Top countries by cumulative cases
-   China case trend
-   Peak daily new cases
-   Recovery-rate comparison
-   Canadian provincial death-rate distribution

### Data Transformation

-   Wide-to-long transformation with `melt()`
-   Date conversion with `pd.to_datetime()`
-   Aggregation by country and date
-   Pivoting country-level data

### Data Merging

Confirmed, deaths, and recovered datasets are transformed and merged
using:

-   `Country/Region`
-   `Date`

### Visualization

-   Line charts
-   Bar charts
-   Box plots
-   Time-series visualizations

## Repository Structure

``` text
COVID-19_Data_Analysis_Python/
│
├── COVID-19_Data_Analysis_Python.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
└── data/
    └── covid_19_dataset.xlsx
```

## How to Run

### 1. Clone the repository

``` bash
git clone https://github.com/YOUR-USERNAME/covid-19-data-analysis-python.git
cd covid-19-data-analysis-python
```

### 2. Install dependencies

``` bash
pip install -r requirements.txt
```

### 3. Open the notebook

``` bash
jupyter notebook
```

Open:

``` text
COVID-19_Data_Analysis_Python.ipynb
```

## Portfolio Skills Demonstrated

**Python:** Pandas, NumPy, Matplotlib, Seaborn

**Data Analysis:** Data Cleaning, EDA, Data Transformation, Aggregation,
Time-Series Analysis, Rate Calculations

**Data Preparation:** Missing-Value Handling, Wide-to-Long
Transformation, Merging, Pivoting

**Business Analytics:** Trend Analysis, KPI Analysis, Comparative
Analysis, Data Visualization

## Important Note

This project analyzes the supplied case-study dataset. COVID-19 datasets
can contain reporting revisions and other data-quality issues, so
results should be interpreted as analysis of the provided data rather
than as an authoritative epidemiological assessment.
