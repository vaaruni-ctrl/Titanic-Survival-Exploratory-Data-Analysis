# Titanic-Survival-Exploratory-Data-Analysis
An Exploratory Data Analysis project investigating the factors associated with passenger survival on the Titanic using Python.


# Titanic Survival – Exploratory Data Analysis

## Project Overview

This project focuses on exploring the Titanic passenger dataset to identify the factors associated with passenger survival during the Titanic disaster of 1912.

Exploratory Data Analysis (EDA) techniques are used to examine passenger characteristics such as age, gender, passenger class, ticket fare, embarkation town, and family size.

The project uses Python for data cleaning, statistical analysis, and data visualization to uncover meaningful patterns and insights.

## Objectives

- Understand the structure and characteristics of the Titanic dataset.
- Identify and handle missing values.
- Analyse passenger demographics and travel information.
- Explore the relationship between passenger characteristics and survival.
- Visualize important patterns using charts and graphs.
- Derive meaningful insights from the analysis.

## Dataset Description

The Titanic dataset was obtained using the Seaborn library.

- Total records: 891 passengers
- Total features after preprocessing: 15
- Target variable: `survived`
- 0 represents passengers who did not survive.
- 1 represents passengers who survived.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

## Data Preprocessing

The following preprocessing steps were performed:

- Examined the dataset structure and data types.
- Identified missing values.
- Replaced missing age values with the median.
- Filled missing embarkation values using the mode.
- Removed the `deck` column due to a high percentage of missing values.
- Created a new feature named `family_size`.
- Examined identical records without automatically removing them, since identical feature values do not necessarily represent the same passenger.

## Exploratory Data Analysis

The analysis was performed in three stages:

### 1. Univariate Analysis
- Survival distribution
- Gender distribution
- Age distribution
- Passenger class distribution
- Fare distribution
- Embarkation town distribution

### 2. Bivariate Analysis
- Gender vs survival
- Passenger class vs survival
- Age vs survival
- Fare vs survival
- Embarkation town vs survival

### 3. Multivariate Analysis
- Gender and passenger class vs survival
- Age and gender vs survival
- Correlation analysis
- Family size vs survival

## Key Findings

- The dataset contains 891 passengers, of whom 342 survived.
- The overall survival rate was approximately 38.38%.
- Female passengers had a considerably higher survival rate (74.20%) than male passengers (18.89%).
- First-class passengers had a higher survival rate (62.96%) compared with second-class (47.28%) and third-class passengers (24.24%).
- Passengers travelling in smaller family groups generally showed higher survival rates than those travelling alone or in larger groups.
- Passengers travelling with a family size of four recorded the highest survival rate (72.41%) among the observed family-size groups.

## Conclusion

The analysis reveals meaningful relationships between passenger characteristics and survival outcomes on the Titanic. Gender and passenger class showed particularly noticeable differences in survival rates. Family size also displayed interesting patterns.

This project demonstrates how Exploratory Data Analysis can be used to understand real-world datasets, identify trends, and communicate insights through data visualization.

## Project Files

- `Titanic_EDA.ipynb` – Complete Python analysis and visualizations.
- `README.md` – Project documentation.

## Author

Data Science Internship Project – Codeatrix
