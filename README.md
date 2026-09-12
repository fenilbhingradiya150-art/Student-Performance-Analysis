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

## 📈 Key Results & Insights

- **Dataset Size:** 1,000 student records with 12 attributes.
- **Average Total Marks:** approximately 199.78.
- **Average Percentage:** approximately 66.59%.
- **Average Study Hours:** approximately 9.84 hours.
- **Percentage Standard Deviation:** approximately 12.86.
- **Minimum Percentage:** approximately 17.33%.

### Correlation Insights

The analysis found positive relationships between individual subject marks and overall Percentage:

| Subject | Correlation with Percentage |
|---|---:|
| Mathematics | 0.53 |
| Science | 0.56 |
| English | 0.47 |

Science showed the strongest correlation with overall Percentage among the three subjects analyzed.

### Regression Insights

- Linear Regression was used to study the relationship between Mathematics marks and Percentage.
- The model produced a slope of approximately **0.386** and an intercept of approximately **39.254**.
- For a Mathematics score of **90**, the model predicted a Percentage of approximately **74.01%**.
- A separate regression model using **StudyHours** to predict Percentage achieved an R² score of approximately **-0.004** and an MAE of approximately **9.49**.

## 📂 Project Structure

```text
Student-Performance-Analysis/
│
├── EDA_Report.html
├── README.md
├── Student_Performance_Analysis.ipynb
├── Student_Performance_Presentation.pptx
├── Student_Performance_Report.pdf
└── student_performance.csv
```

### 📄 File Description

| File | Description |
|---|---|
| `Student_Performance_Analysis.ipynb` | Main Jupyter Notebook containing the complete analysis |
| `student_performance.csv` | Student performance dataset |
| `EDA_Report.html` | HTML version of the exploratory data analysis report |
| `Student_Performance_Presentation.pptx` | Project presentation |
| `Student_Performance_Report.pdf` | Detailed project report |
| `README.md` | Project documentation |

## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/fenilbhingradiya150-art/Student-Performance-Analysis.git
```

### 2. Navigate to the Project Directory

```bash
cd Student-Performance-Analysis
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the Notebook

Open:

```text
Student_Performance_Analysis.ipynb
```

Run the notebook cells sequentially to reproduce the analysis.

### 6. Dataset

Make sure `student_performance.csv` is present in the same project directory as the notebook.

## 📚 Reports & Resources

The following project resources are included in this repository:

- 📓 **[Jupyter Notebook](./Student_Performance_Analysis.ipynb)** — Complete analysis and implementation.
- 📊 **[EDA Report](./EDA_Report.html)** — Exploratory Data Analysis report.
- 📄 **[Project Report](./Student_Performance_Report.pdf)** — Detailed project documentation.
- 📑 **[Project Presentation](./Student_Performance_Presentation.pptx)** — Project presentation.
- 📁 **[Dataset](./student_performance.csv)** — Student performance dataset.

## 👨‍💻 Author

### Fenil Bhingradiya

Aspiring Software Engineer | Full-Stack Web Developer | C++ & DSA

- 💼 LinkedIn: [linkedin.com/in/fenil-bhingradiya]
- 🐙 GitHub: [https://github.com/fenilbhingradiya150-art]
- 📧 Email: fenilbhingradiya150@gmail.com
