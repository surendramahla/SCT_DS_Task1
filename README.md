# SCT_DS_Task1
# 📊 SkillCraft Data Science Task 1

This repository contains the solution for **Task 1** of the SkillCraft Data Science challenge. The task focuses on performing data analysis and creating meaningful visualizations using population datasets and internal demographic data.

---

## 📝 Task Description

**Objective:**  
Analyze the World Bank population data and present key insights. Additionally, visualize internal employee demographic data (like age distribution) for SkillCraft Technology.

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `ques1.py` | Python script for data analysis and visualizations |
| `API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv` | Population dataset from World Bank |
| `README.md` | Project documentation |
| `top10_population_bar.png` | Bar chart: Top 10 most populous countries (2022) |
| `population_histogram.png` | Histogram: Population distribution |
| `skillcraft_age_distribution.png` | Age distribution at SkillCraft Technology |

---

## 🧪 Key Features & Visualizations

### 1. 🌍 Population Distribution Histogram (2022)
Uses a **log scale** for the population axis to better represent countries with large differences in population.

**Preview:**
![Population Histogram](population_histogram.png)

---

### 2. 🌐 Top 10 Most Populous Countries (2022)
A horizontal bar chart showing the top 10 countries by population, using the latest available World Bank data.

**Preview:**
![Top 10 Countries Bar Chart](top10_population_bar.png)

---

### 3. 🧑‍💼 SkillCraft Age Distribution
Bar chart showing the number of people in various age brackets within the company.

**Preview:**
![SkillCraft Age Distribution](skillcraft_age_distribution.png)

---

## 🚀 How to Run the Code

### Step 1: Install dependencies
```bash
pip install pandas matplotlib seaborn
