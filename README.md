# Insurance Data Analysis

## Project Overview

This project explores and analyses an insurance dataset using **Python** and **Tableau** to uncover factors that influence medical insurance charges. The primary goal is to derive actionable insights related to customer demographics, lifestyle factors (e.g., smoking), and their impact on insurance premiums. The insights support data-driven decision-making for premium pricing and customer segmentation.

---

## Problem Statement

An insurance provider wants to:

- Understand how various factors like age, BMI, gender, children, region, and smoking habits influence insurance charges.
- Identify which customer segments are at high risk (and thus high cost).
- Build a foundation for further predictive modeling or premium adjustment strategies.

The solution involves analyzing a single structured dataset:

- `insurance.csv`: Contains detailed records of individual insurance policyholders with 7 key attributes.

---

## Technologies Used

- **Python** (with libraries: pandas, seaborn, matplotlib, numpy)
- **Jupyter Notebook** for data cleaning and EDA
- **Tableau** for interactive data visualization
- **Git & GitHub** for version control and publishing

---

## Data Understanding & Cleaning

The following preprocessing steps were performed:

- Inspected data structure and column data types
- Verified data completeness – no missing values were found
- Checked for duplicates
- Categorical/numerical column identification for appropriate visual treatment
- Outlier and distribution checks for key variables

---

## Exploratory Data Analysis (EDA)

Key questions explored using Python:

### Demographics & Distribution:

- What is the gender and region distribution of the insured population?
- What is the smoker vs non-smoker ratio?
- How many children are typically covered?

### Cost & Risk Insights:

- How do **age**, **BMI**, and **smoking status** affect **insurance charges**?
- Do **smokers pay more** than non-smokers?
- Does **having more children** impact premiums?
- Is there a relationship between **obesity (BMI)** and charges?

### Key Relationships:

- Scatter plots to explore numerical feature impact on charges
- Count plots to visualize distribution of categorical features

---

## Tableau Dashboard

The **Tableau dashboard** provides a clean, interactive view of how various customer features impact insurance charges:

### Visual Elements:

- **Categorical Analysis:** Bar charts for smoker, sex, and region distribution
- **Charges vs Age:** Scatter plot with smoker color split and trend line
- **BMI vs Charges:** Scatter plot to show effect of body mass on cost
- **Charges vs Number of Children:** To check cost differences for families
- **Filters:** User can filter dashboard by `smoker`, `sex`, or `region`

### Link to Tableau Public Dashboard:
[View Dashboard on Tableau Public](https://public.tableau.com/app/profile/viijeta.r/viz/InsuranceDataAnalysis_17522524069880/InsuranceDataAnalysis?publish=yes)

---

## Key Findings

- **Smokers pay significantly higher insurance charges**, especially as they age.
- **Age and BMI are positively correlated** with charges.
- **Number of children** has minimal impact on cost.
- **Non-smokers have consistently lower premiums** across all age groups.

---

## Author

**Vijeta** – Junior Data Analyst  
Tools: Python | Tableau | SQL | Power BI  | Excel
[🔗 Connect on LinkedIn](https://www.linkedin.com/in/viijetar/)
