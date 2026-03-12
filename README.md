# Sustainable-Consumer-Behavior-Analysis
# Sustainable Consumer Behavior Analysis

## Overview

This project analyzes a **consumer survey dataset** to understand factors that influence purchasing behavior related to sustainability and product availability. The notebook performs **data cleaning, missing value analysis, statistical exploration, and machine learning modeling** to extract insights from the dataset.

The workflow includes:

* Data loading and preprocessing
* Handling missing values
* Exploratory Data Analysis (EDA)
* Statistical testing
* Visualization
* Machine learning evaluation

The goal of the project is to identify relationships between **consumer demographics, brand loyalty, price perception, and product availability**.

---

## Dataset

The dataset contains survey responses with the following variables:

| Column             | Description                                 |
| ------------------ | ------------------------------------------- |
| ID                 | Unique respondent identifier                |
| IQ1_Gender         | Gender of the respondent                    |
| IQ2_Age            | Age group of the respondent                 |
| IQ3_OutOfStock     | Experience with products being out of stock |
| IQ4_QualityVsPrice | Opinion on quality vs price                 |
| IQ5_BrandLoyalty   | Level of loyalty to a brand                 |
| IQ6_SameBrand      | Likelihood of buying the same brand again   |

The dataset is uploaded directly in the notebook environment.

---

## Project Workflow

### 1. Install and Import Libraries

The notebook installs and imports common Python data science libraries:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* scipy
* statsmodels
* shap
* missingno

---

### 2. Data Upload

The dataset is uploaded and loaded into a pandas DataFrame.

Example:

```python
df = pd.read_csv(file_name, encoding='latin1')
```

---

### 3. Data Cleaning

Cleaning steps include:

* Removing unwanted index columns
* Renaming dataset columns
* Handling missing values
* Filling categorical missing values with the mode
* Fixing ID values

---

### 4. Missing Value Analysis

The project visualizes missing data using the **missingno** library:

* Missing value matrix
* Missing value count bar chart

These visualizations help understand data completeness.

---

### 5. Exploratory Data Analysis (EDA)

EDA includes:

* Distribution analysis
* Relationship visualization
* Correlation understanding
* Consumer behavior patterns

Visualization libraries used:

* Matplotlib
* Seaborn

---

### 6. Statistical Analysis

Statistical tests such as **Chi-Square tests** are used to analyze relationships between categorical variables.

Example:

```python
from scipy.stats import chi2_contingency
```

---

### 7. Machine Learning & Evaluation

The notebook includes machine learning evaluation techniques such as:

* ROC Curve
* AUC score
* Model interpretation using SHAP

These methods help evaluate prediction performance and understand feature importance.

---

## Visualizations

The project generates several plots including:

* Missing value matrix
* Missing value count bar chart
* ROC curves
* Statistical relationship plots

These visualizations help interpret the survey results effectively.

---

## Requirements

Install required libraries before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy statsmodels shap missingno
```

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/repository-name.git
```

2. Open the notebook

```bash
jupyter notebook
```

3. Upload the dataset when prompted.

4. Run all cells sequentially.

---

## Project Structure

```
project-folder/
│
├── Sustainable_draft_2_fixed_outputs.ipynb
├── dataset.csv
└── README.md
```

---

## Purpose of the Project

This project helps researchers and analysts:

* Understand **consumer purchasing behavior**
* Analyze **brand loyalty patterns**
* Evaluate the impact of **price vs quality perception**
* Study **supply availability effects (out-of-stock issues)**

---

## Author

Samia

