# Adult Income Analysis (Junior Data Analyst Project)

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)](https://pandas.pydata.org)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557c?style=flat)
![Scikit-Learn](https://img.shields.io/badge/sklearn-0.17stable-brightgreen.svg)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()
---

## 📋 Table of Contents

- [Overview](#-overview)
- [Dataset Description](#-Dataset Description)
- [Objectives](#-Objectives)
- [Methodology](#-Methodology)
- [Technologies Used](#-Technologies Used)
- [How to Run](#-How to Run)
- [Key Findings (Preview)](#-Key Findings (Preview))
- [Contact](#-Contact)


---

## 📌 Overview
This project performs a **Junior-level Exploratory Data Analysis (EDA)** on the famous **Adult Income Dataset** (Census Income). The goal is to understand demographic factors influencing income inequality and to build a simple baseline model to predict whether an individual earns more than $50K/year.

This workflow is designed to be **beginner-friendly**, using core Python libraries without over-complicating feature engineering or model tuning.

## 📂 Dataset Description
The dataset consists of approximately **48,842 records** extracted from the 1994 Census database. It includes the following key attributes:

1.  **Age**: Continuous variable.
2.  **Workclass**: Employment category (e.g., Private, Self-emp, Government).
3.  **Education**: Highest education level attained.
4.  **Marital Status**: Marital status of the individual.
5.  **Occupation**: Type of job.
6.  **Relationship**: Relationship status in the family.
7.  **Race & Gender**: Demographic identifiers.
8.  **Capital Gain/Loss**: Income from investment sources.
9.  **Hours per week**: Average working hours.
10. **Native Country**: Country of origin.
11. **Income (Target)**: Binary variable (`<=50K` or `>50K`).

> **Note:** The dataset contains missing values represented as **`?`**, which are handled during the cleaning phase.

## 🎯 Objectives
The main goals of this analysis are:

- **Data Cleaning**: Identify and handle special missing characters (`?`) and duplicate rows.
- **Exploration**: Analyze distributions of Age, Education, and Hours-per-week.
- **Insights**: Discover how Gender, Marital Status, and Occupation relate to Income levels.
- **Modeling**: Establish a simple **Logistic Regression** baseline to predict income.

## ⚙️ Methodology

### 1. Data Cleaning
- **Handling '?'**: Converted the placeholder `?` to `NaN`.
- **Strategy**: Rows with missing values in categorical columns (`workclass`, `occupation`, `native-country`) were dropped for simplicity (Junior approach).
- **Formatting**: Stripped extra whitespaces from categorical strings to ensure consistency.

### 2. Exploratory Data Analysis (EDA)
- **Visualizations**: Used `matplotlib` to plot histograms for Age and Hours-per-week.
- **Group Analysis**: Calculated mean Age and Hours-per-week grouped by Income class.
- **Crosstabs**: Created pivot tables to observe the probability of earning >50K based on Education and Marital Status.

### 3. Machine Learning (Baseline)
- **Preprocessing**: Applied One-Hot Encoding to categorical variables.
- **Model**: Used `LogisticRegression` from `scikit-learn`.
- **Evaluation**: Assessed performance using Accuracy Score and Classification Report.

## 🛠️ Technologies Used
- **Python 3.x**
- **Pandas**: Data manipulation and cleaning.
- **NumPy**: Numerical operations.
- **Matplotlib**: Basic data visualization.
- **Scikit-Learn**: Simple predictive modeling.

## 🚀 How to Run
1.  Ensure `adult.csv` is in the same directory as the notebook.
2.  Install dependencies if needed:
bash
pip install pandas numpy matplotlib scikit-learn
3. Open the Jupyter Notebook and run all cells sequentially.
## 📊 Key Findings (Preview)
- Education Impact: Higher education levels (Bachelors, Masters, Doctorate) significantly correlate with >50K income.
- Age Factor: Higher income earners tend to be older on average than lower income earners.
- Work Hours: Individuals earning >50K work slightly more hours per week on average.

## 📬 Contact
|Platform |	Link |
|---------|------|
|📧 Email |	jenabfarzad@yahoo.com |
|💼 LinkedIn |	farzadjenab |
|🐙 GitHub	| @farzadjenab |

--- 

<div align="center">

**⭐ If you found this project helpful, please give it a star! ⭐**

[![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red.svg)]()
[![Python](https://img.shields.io/badge/Powered%20by-Python-blue.svg)]()

</div>
