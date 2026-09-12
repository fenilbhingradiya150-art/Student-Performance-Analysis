# 📊 Student Performance Analysis

## 📌 Project Overview

Student Performance Analysis is a Python-based data analysis project focused on exploring student academic performance through data preprocessing, Exploratory Data Analysis (EDA), statistical analysis, data visualization, correlation analysis, and regression modeling.

The project analyzes a dataset containing **1,000 student records and 12 attributes** related to academic performance, demographics, extracurricular activities, and study habits.

## 🎯 Objectives

- Analyze student academic performance using Python.
- Perform Exploratory Data Analysis (EDA).
- Identify relationships between subjects and overall performance.
- Visualize important patterns and distributions in the dataset.
- Apply correlation and regression analysis.
- Evaluate the relationship between study hours and percentage.

## 🛠️ Technologies & Libraries

- **Python** — Programming language
- **Pandas** — Data manipulation and analysis
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical data visualization
- **Scikit-learn** — Regression and machine learning
- **Jupyter Notebook** — Interactive data analysis

## 📊 Dataset

The dataset contains **1,000 student records** and **12 attributes** covering academic performance, demographics, extracurricular activities, and study habits.

### Dataset Attributes

| Column | Description |
|---|---|
| `id` | Unique student identifier |
| `age` | Student age |
| `gender` | Student gender |
| `math` | Mathematics marks |
| `science` | Science marks |
| `english` | English marks |
| `sports` | Sports participation |
| `music` | Music participation |
| `Total Marks` | Total academic marks |
| `Percentage` | Overall percentage |
| `GradeClass` | Student grade classification |
| `StudyHours` | Hours spent studying |

### Missing Values

The dataset contains missing values in the following columns:

- `math` — 50 missing values
- `science` — 48 missing values
- `english` — 49 missing values
- `sports` — 50 missing values

## 🔍 Analysis Performed

### 1. Data Loading & Preprocessing

- Loaded the student performance dataset using Pandas.
- Inspected the dataset structure, columns, data types, and records.
- Identified missing values in academic and extracurricular attributes.
- Prepared the data for statistical and visualization-based analysis.

### 2. Exploratory Data Analysis (EDA)

- Examined the distribution of student percentages.
- Used histograms to understand percentage distribution.
- Used box plots to identify the spread and possible outliers.
- Analyzed relationships between academic subjects and overall percentage.

### 3. Statistical Analysis

- Calculated descriptive statistics such as mean, minimum, maximum, and standard deviation.
- Analyzed covariance between variables.
- Performed correlation analysis to identify relationships between academic subjects and percentage.

### 4. Correlation Analysis

- Created a correlation matrix for numerical variables.
- Visualized correlations using a heatmap.
- Studied the relationship between Mathematics, Science, English, and overall Percentage.

### 5. Regression Analysis

- Applied Linear Regression to analyze the relationship between Mathematics marks and Percentage.
- Used StudyHours as an independent variable to predict student Percentage.
- Evaluated the regression model using R² and Mean Absolute Error (MAE).

### 6. Model Evaluation

- Demonstrated the concepts of overfitting and underfitting.
- Compared training and testing performance using Linear Regression and Decision Tree models.
