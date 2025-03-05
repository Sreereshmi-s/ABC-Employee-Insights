# ABC Employee Analysis

## 📌 Project Overview
This project analyzes ABC employee data to uncover key trends, distributions, and correlations within the dataset. The analysis includes data preprocessing, visualization, and insights into employee distribution, salary expenditure, and age-based trends.

## 📂 Dataset
- **File Name:** `myexcel.csv`
- **Columns Included:** `Name`, `Age`, `Height`, `Team`, `Position`, `Salary`

## 🛠️ Preprocessing Steps
1. **Handling Missing Values:**
   - Checked for null values and handled them by filling numerical columns with mean/median and categorical columns with the mode.
2. **Correcting Height Data:**
   - Replaced the "Height" column with random values between 150 cm and 180 cm to maintain consistency.
3. **Ensuring Data Integrity:**
   - Verified data types and removed inconsistencies.

## 📊 Analysis Tasks
### 1️⃣ Employee Distribution by Team
- Counted employees per team and calculated their percentage relative to the total workforce.
- **Visualization:** 📈 Bar chart representing employee distribution.

### 2️⃣ Employee Segregation by Position
- Counted the number of employees in different job positions.
- **Visualization:** 📊 Bar chart showing the frequency of each position.

### 3️⃣ Predominant Age Group
- Categorized employees into age groups (18-24, 25-30, 31-35, 36-40) and identified the most common group.
- **Visualization:** 📉 Bar chart displaying the most frequent age group.

### 4️⃣ Highest Salary Expenditure (Team & Position)
- Identified which team and position have the highest total salary expenditure.
- **Visualization:** 💰 Bar charts comparing salary expenditure by team and position.

### 5️⃣ Correlation Between Age and Salary
- Analyzed if age has a significant impact on salary using correlation analysis.
- **Visualization:** 🔍 Scatter plot showing the relationship between age and salary.

## 🔍 Key Insights
- **Employee Distribution:** The team with the highest number of employees was identified, while some teams had fewer employees.
- **Position Trends:** Shooting Guards (SG) were the most common, while Centers (C) were the least common.
- **Age Distribution:** The majority of employees fell within the 25-30 age group.
- **Salary Analysis:** The Cleveland Cavaliers had the highest salary expenditure, and Centers (C) earned the highest total salaries.
- **Age vs. Salary:** A weak positive correlation was observed between age and salary, suggesting that experience may play a role but is not the only determining factor.

## 📈 Visualizations
All analysis tasks are accompanied by appropriate visualizations using **Matplotlib** and **Seaborn** for better understanding and insights.

## 🚀 How to Run the Project
1. **Clone this repository:**
   ```bash
   git clone https://github.com/Sreereshmi-s/ABC-Employee-Insights.git
   ```
2. **Open the Jupyter Notebook and execute the cells in order.**

## 📁 Repository Structure
```
├── ABC Employee Insights.ipynb  # Jupyter Notebook containing the analysis
├── myexcel.csv                   # Dataset used for analysis
├── README.md                      # Project documentation
```

## ✍️ Author
- **Sreereshmi S**
- **Date:** March 2025

