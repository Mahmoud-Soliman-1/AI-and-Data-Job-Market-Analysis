# AI-and-Data-Job-Market-Analysis

## 📌 Project Overview
This project analyzes global data-related job salaries from an HR perspective and builds a machine learning model to predict expected salaries based on candidate attributes.

The goal is to help HR professionals:
- Understand salary trends in the data field
- Compare roles, experience levels, and company factors
- Estimate fair salary ranges for candidates

---

## 📁 Dataset Description

The dataset contains information about data professionals, including:

- `work_year`
- `experience_level`
- `employment_type`
- `job_title`
- `salary`
- `salary_currency`
- `salary_in_usd`
- `employee_residence`
- `remote_ratio`
- `company_location`
- `company_size`

---

## 🧹 Data Preparation

Steps performed using Python:

- Merged multiple data sources
- Removed duplicates
- Handled missing values
- Standardized salaries using `salary_in_usd`
- Created new features:
  - `job_category` (grouped job titles into major categories)
  - `same_country` (whether employee and company are in the same country)

---

## 📊 Data Analysis (Power BI Dashboard)

A full interactive dashboard was created to analyze the market from an HR perspective.

### 🔹 Page 1: Market Overview
- Median Salary
- Headcount
- Remote Work Percentage
- Salary Trend Over Time
- Salary by Job Function
- Job Distribution
- Remote Distribution

### 🔹 Page 2: Experience & Company Analysis
- Salary by Experience Level
- Salary by Company Size
- Combined impact of experience and company size

### 🔹 Page 3: Location & Remote Analysis
- Salary by Country
- Remote vs Onsite distribution by location
- Cross-country employment insights

---

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy, )
- Power BI
- Data Cleaning & EDA

---


## 📬 Contact

Mahmoud Soliman  
Data Analyst  
mahmoudsoliman1503@gmail.com
---


