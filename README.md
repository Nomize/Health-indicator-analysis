# 🩺 Health Indicators Analysis (Diabetes & Heart Disease)

This project explores a **Binary Health Indicators dataset** (Kaggle), focusing on risk factors related to **diabetes and heart disease**.  
The analysis was carried out step by step following the assignment requirements: data loading, cleaning, exploration, basic analysis, and visualizations.

---

## 📌 Project Overview

**Objective:**  
To practice Python data analysis using **pandas** for data handling and **matplotlib/seaborn** for visualizations.  

**Tasks Covered:**  
1. **Load & Explore the Dataset**  
2. **Basic Data Analysis**  
3. **Data Visualization**  
4. **Summary & Key Insights**

---

## 🛠️ Tools & Libraries Used

- [Python 3.x](https://www.python.org/)  
- [Jupyter Notebook](https://jupyter.org/)  
- [Pandas](https://pandas.pydata.org/) – data loading & exploration  
- [Matplotlib](https://matplotlib.org/) – core visualizations  
- [Seaborn](https://seaborn.pydata.org/) – improved chart aesthetics  

---

## 📂 Dataset

The dataset was downloaded from **Kaggle**:  
- **binary_health_indicators.csv** (used for analysis)  
- It includes features such as:  
  - **Diabetes indicators:** `HighBP`, `HighChol`, `BMI`, `Smoker`, `Stroke`  
  - **Heart disease indicators:** `PhysicalActivity`, `Fruits`, `AnyHealthcare`  
  - **Demographics:** `Sex`, `Age`, `Education`, `Income`

---

## ✅ Task 1: Load and Explore the Dataset

- Imported the dataset with `pandas.read_csv()`  
- Checked the **first 5 rows** with `.head()`  
- Verified **data types** and **missing values** with `.info()` and `.isnull().sum()`  
- Cleaned missing values (dropped or filled where necessary)  

---

## 📊 Task 2: Basic Data Analysis

- Generated **descriptive statistics** with `.describe()`  
- Computed group-wise averages using `.groupby()` (e.g., `Age` vs. `BMI`)  
- Observed patterns: higher BMI linked with diabetes risk, lower physical activity in older groups, etc.  

---

## 📈 Task 3: Data Visualization

Four main plots were created:

1. **Line Chart** – Trend of physical activity by age group  
2. **Bar Chart** – Average BMI per age group  
3. **Histogram** – Distribution of BMI across the dataset  
4. **Scatter Plot** – Relationship between BMI and Stroke incidence  

✔️ All charts were customized with **titles, axis labels, and legends**.  
✔️ Seaborn was used to improve **aesthetics**.  

---

## ⚠️ Error Handling

- Used **try-except blocks** to handle issues such as:  
  - Missing files (`FileNotFoundError`)  
  - Invalid data types  
- Ensured the analysis runs smoothly even with unexpected errors.  

---

## 📝 Final Summary / Findings

- **Obesity (BMI) and High Blood Pressure** are strong risk factors for diabetes.  
- **Physical activity declines with age**, increasing risks of chronic diseases.  
- **Healthcare access** is uneven, affecting long-term outcomes.  
- **Socioeconomic status (income, education)** is linked to disparities in health.  

➡️ **Conclusion:** Healthy lifestyle habits, preventive care, and equitable healthcare access are key to reducing the burden of diabetes and heart disease.  

---

## 📌 How to Run the Project

1. Clone this repository:  
   ```bash[
   git clone https://github.com/Nomize/Health-indicator-analysis.git
