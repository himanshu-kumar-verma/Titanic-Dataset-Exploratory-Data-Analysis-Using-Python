# Titanic Dataset – Exploratory Data Analysis (EDA) using Python

## 📌 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Titanic dataset to
understand the structure of the data, identify patterns, trends, relationships, and anomalies
using visual and statistical techniques.

EDA helps in gaining insights into the factors that influenced passenger survival on the Titanic.


## 🎯 Objective
- Perform Exploratory Data Analysis on the Titanic dataset
- Understand data distribution and structure
- Identify relationships between variables
- Detect patterns, trends, and anomalies
- Summarize key insights using visualizations


## 📂 Dataset
- **Source:** Kaggle – Titanic Dataset
- **Files Used:** `train.csv`
- **Rows:** 891
- **Columns:** 12
- **Target Variable:** `Survived`

> Note: Only `train.csv` is used for EDA because it contains the target variable (`Survived`).
The test and submission files are used in the modeling phase.


## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook


## 🔍 EDA Steps Performed

### 1. Data Loading
- Loaded the dataset using Pandas
- Displayed initial rows to understand data structure

### 2. Initial Data Exploration
- Checked dataset shape
- Inspected column data types and missing values
- Generated statistical summary using `.describe()`

### 3. Missing Value Analysis
- Identified missing values using `.isnull().sum()`
- Observed missing data mainly in `Age` and `Cabin` columns

### 4. Univariate Analysis
- Survival distribution
- Gender distribution
- Age distribution using histograms
- Outlier detection using boxplots

### 5. Bivariate Analysis
- Survival vs Gender
- Survival vs Passenger Class
- Age vs Survival

### 6. Multivariate Analysis
- Pair plot for numerical feature relationships
- Correlation heatmap to identify feature dependencies


## 📊 Key Insights
- Female passengers had significantly higher survival rates than males
- First class passengers survived more than third class passengers
- Younger passengers had better chances of survival
- Higher fare values are associated with higher survival probability
- Age and Fare columns contain outliers


## ✅ Conclusion
Exploratory Data Analysis provided valuable insights into the Titanic dataset.
Clear relationships were observed between survival and factors such as gender,
passenger class, and fare. These insights can be used for feature selection
and predictive modeling in future steps.


## 📁 Project Structure
- Titanic Dataset
  - train.csv
  - test.csv
  - gender_submission.csv
- Titanic_EDA_Jupyter_Notebook
  - Titanic_EDA.ipynb
  - PDF Report
- Readme.md


## 🚀 How to Run This Project
1. Clone the repository
2. Open Jupyter Notebook
3. Run `Titanic_EDA.ipynb` step by step
4. Ensure required libraries are installed
5. Export notebook as PDF if required


## 📈 Deliverables
- Jupyter Notebook with EDA
- PDF report of findings
- Clear visualizations with observations


## 🔮 Future Work
- Handle missing values using imputation techniques
- Perform feature engineering
- Build machine learning models for survival prediction
- Evaluate model performance


## 👤 Author
**Name:** Himanshu Kumar Verma 
**Role:** Data Analysis Intern / Aspiring Data Analyst  
**Skills:** Python, EDA, Data Visualization  


## 📬 Contact
- GitHub: https://github.com/himanshu-kumar-verma
- LinkedIn: https://www.linkedin.com/in/himanshu-kumar-verma2003
