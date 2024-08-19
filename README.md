# LifeExpectancy
## Project Overview

## Data Source
The dataset for this project is sourced from the [Global Health Observatory (GHO) under the World Health Organization (WHO)](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who/data). This dataset includes life expectancy and various health-related factors for 193 countries from 2000 to 2015. Additional economic data was obtained from the United Nations website.

## Context
Although numerous studies have explored factors affecting life expectancy, many have overlooked the impact of immunization and the Human Development Index (HDI). Additionally, some past research relied on multiple linear regression models using data from a single year for all countries. This project addresses these gaps by:

- **Incorporating Immunization Factors**: Including critical immunizations such as Hepatitis B, Polio, and Diphtheria.
- **Using Longitudinal Data**: Analyzing data spanning from 2000 to 2015 to capture trends over time.
- **Employing Advanced Models**: Utilizing both mixed effects models and multiple linear regression to enhance the analysis.

The study aims to examine the impact of immunization, mortality, economic, social, and other health-related factors on life expectancy. By analyzing data from multiple countries, the project seeks to identify key predictors of life expectancy, providing actionable insights for policy-making and health improvement strategies.

## Content
The project relies on accurate data provided by the WHO and the United Nations. The dataset consists of health and economic factors for 193 countries over a 15-year period. The data was carefully processed as follows:

1. **Data Collection**: Health data was sourced from the WHO, while economic data was collected from the United Nations.
2. **Data Integration**: Individual data files were merged into a single dataset.
3. **Missing Data Handling**: Initial inspection revealed missing values, particularly for population, Hepatitis B, and GDP. Missing data was addressed using the `Missmap` command in R, and countries with significant gaps were excluded from the analysis. The final dataset contains 22 columns and 2938 rows, representing 20 predicting variables.

## Table of Contents

1. [Data Loading](#data-loading)
2. [Basic Analysis](#basic-analysis)
3. [Null Value Analysis & Imputations](#null-value-analysis--imputations)
4. [Outliers Analysis & Handling](#outliers-analysis--handling)
5. [Categorical Data Imputation](#categorical-data-imputation)
6. [Regression Analysis](#regression-analysis)
7. [Model Building & Hyperparameter Tuning](#model-building--hyperparameter-tuning)

### Data Loading
Details the process of loading and importing the dataset into the analysis environment. This section includes the sources of the data and any initial data setup.

### Basic Analysis
Provides an overview of the initial exploratory data analysis (EDA). This includes summary statistics, data types, and basic visualizations to understand the dataset.

### Null Value Analysis & Imputations
Covers the analysis of missing values in the dataset and the methods used to handle them. This includes techniques for imputing missing values and any decisions made regarding excluded data.

### Outliers Analysis & Handling
Describes the process of identifying and managing outliers in the dataset. This section explains the methods used to detect outliers and how they were addressed or removed.

## Categorical Data Imputation
Explains the approach for dealing with categorical data, including how missing values in categorical features were imputed or handled.

### Regression Analysis
Details the regression analysis performed, including the types of regression models used, the variables considered, and the overall findings from the regression analysis.

### Model Building & Hyperparameter Tuning
Describes the process of building and optimizing the regression models. This includes selecting models, tuning hyperparameters, and evaluating model performance.


### Acknowledgements
The successful completion of this project was made possible with the assistance of Deeksha Russell and Duan Wang. Their support in data collection and analysis was invaluable.
