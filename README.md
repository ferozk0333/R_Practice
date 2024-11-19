# IMT 573 A: Data Science 1 - Theoretical Foundations

This repository contains problem sets completed as part of the course **IMT 573 A: Data Science 1 - Theoretical Foundations** at the **University of Washington**. The assignments explore a wide range of data science concepts, statistical techniques, and programming in R. Each assignment addresses real-world datasets, enabling hands-on learning and application of theoretical foundations.

## Overview

The assignments cover a broad array of data science topics, including:

- **Data Manipulation**: Cleaning, transforming, and merging datasets.
- **Statistical Analysis**: Hypothesis testing, confidence intervals, and regression modeling.
- **Visualization**: Using `ggplot2` to create compelling visualizations.
- **Web Scraping**: Extracting and processing data from online sources.
- **Simulations**: Monte Carlo methods and probability-based experiments.
- **Modeling**: Simple and multiple linear regression analysis.

## Key Concepts

1. **Exploratory Data Analysis (EDA)**:
   - Examined datasets like **NYC Flights**, **Seattle Crime Data**, and **Boston Housing Data**.
   - Computed descriptive statistics (mean, median, standard deviation, etc.).
   - Created insightful visualizations using R's `ggplot2`.

2. **Statistical Foundations**:
   - Hypothesis testing using `t-tests`.
   - Probability distributions (Normal, Binomial) for data modeling.

3. **Regression Modeling**:
   - Simple and multiple linear regression models.
   - Interpretation of coefficients, \( R^2 \), and adjusted \( R^2 \).
   - Addressing real-world challenges in datasets like house prices and restaurant pricing.

4. **Web Scraping**:
   - Extracted data from Wikipedia tables (e.g., mountain elevation data).
   - Used `rvest` and `tidyverse` for parsing and analyzing HTML content.

5. **Simulation Studies**:
   - Designed simulations to study relationships, such as father-son height analysis.
   - Applied Monte Carlo simulations to validate statistical inferences.

## Datasets Used

1. **Boston Housing Data**: Used for regression analysis on housing prices in Boston suburbs.
2. **Fatherson Height Data**: Studied the correlation between father and son heights.
3. **NYC Flights Dataset**: Analyzed flight delays and their causes.
4. **Seattle Crime Data**: Explored patterns and trends in Seattle crime reports.
5. **COVID-19 Data**: Modeled and visualized the spread and impact of the pandemic.
6. **Wikipedia Mountain Data**: Extracted and mapped high-elevation mountains worldwide.
7. **Zagat Restaurant Data**: Analyzed factors affecting restaurant meal prices in NYC.

## Key Libraries

The assignments make extensive use of the following R libraries:

- **tidyverse**: Core data manipulation and visualization.
- **ggplot2**: Data visualization.
- **dplyr**: Data manipulation and filtering.
- **rvest**: Web scraping and parsing HTML data.
- **lubridate**: Date-time manipulation.
- **MASS**: Modern applied statistics functions.
- **broom**: Tidying statistical results.
- **nycflights13**: Access to NYC flights data.

## Getting Started

### Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/your-repository-name.git

2. Install Package:

   ```bash
   install.packages(c("tidyverse", "rvest", "ggplot2", "MASS", "lubridate"))

3. Run Assignments:

  -  Open .Rmd files in RStudio.
  -  Knit them to generate reports in PDF or HTML format.

4. Acknowledgments:
Professor Tanu Mitra for guidance in this course.

### Repository Structure

├── ProblemSet1.Rmd
├── ProblemSet2.Rmd
├── ProblemSet3.Rmd
├── ProblemSet4.Rmd
├── ProblemSet5.Rmd
├── ProblemSet6.Rmd
├── ProblemSet7.Rmd
├── data/
│   ├── fatherson.csv
│   ├── boston.csv
│   ├── nycflights.csv
│   ├── zagat.csv
│   └── ...
├── README.md
└── figures/
    ├── scatterplot.png
    ├── histogram.png
    └── ...

