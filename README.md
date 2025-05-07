# EDA-and-Visualization-of-Titanic-Dataset


This project focuses on performing **Exploratory Data Analysis (EDA)** on the Titanic dataset, which contains information about passengers aboard the RMS Titanic. The goal is to clean the dataset, visualize key aspects, and derive insights to better understand the data.

## Dataset Overview
The Titanic dataset includes various passenger attributes such as:
- **Demographic Information**: `Sex`, `Age`, `SibSp` (siblings/spouses aboard), `Parch` (parents/children aboard).
- **Ticket Information**: `Pclass` (passenger class), `Fare`, `Cabin`, `Ticket`.
- **Survival Information**: `Survived` (0 = No, 1 = Yes), `Embarked` (port of embarkation).

## Project Steps

### 1. Data Cleaning
The dataset is cleaned by handling missing values, removing duplicates, and addressing outliers. Missing values are imputed where appropriate, and outliers in numeric features (such as `Fare`) are managed using statistical techniques.

### 2. Visualizations
Key visualizations are created to understand the distribution of variables and relationships between them:
- **Bar charts** for categorical features (e.g., `Sex`, `Pclass`, `Embarked`).
- **Histograms** for numeric distributions (e.g., `Age`, `Fare`).
- A **correlation heatmap** to explore relationships between numeric features.

### 3. Key Insights
Some of the key insights derived from the analysis include:
- **Survival Rate by Gender**: Females had a significantly higher survival rate than males.
- **Survival Rate by Class**: Passengers in the first class had the highest survival rates.
- **Age Distribution**: Most passengers were between 20-40 years old.
- **Fare Distribution**: Fare values had some extreme outliers, which were handled through transformation techniques.

### 4. Outlier Management
Outliers in the `Fare` column were identified and managed using techniques like **Interquartile Range (IQR)** and **Winsorization**, where extreme values were capped to reduce their impact.

## Installation

The repositery contains a .ipynb file which can be uploaded on notebook (like google colab and jupyter)

Requirements
pandas, numpy, matplotlib, seaborn

**SUMMARY**


Gender and Survival: Females had a higher survival rate than males.

Passenger Class Impact: First-class passengers were more likely to survive than those in third class.

Age Distribution: Most passengers were between 20-40 years old.

Fare Outliers: Some passengers paid significantly more; log-transforming Fare might help with modeling.

Correlation Insight: Fare and Pclass show a moderate inverse correlation.


