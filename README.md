# Air Pollution Data Analysis Project

## Project Overview
This project analyzes **air pollution data** to understand patterns, trends, and relationships between pollution levels and factors such as **year, season, location, and pollutant indicators**.  

The analysis was performed using **Python for exploratory data analysis and visualization**, and an interactive dashboard was created using Microsoft Power BI.

The goal of this project is to identify **pollution trends, seasonal variations, and high-pollution locations** to better understand environmental patterns.

---

## Objectives
- Analyze air pollution data using data analysis techniques
- Identify **pollution trends over time**
- Compare pollution levels across **seasons and locations**
- Understand relationships between **different pollutants**
- Build an **interactive Power BI dashboard**

---

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Microsoft Power BI

---

## Dataset Description

The dataset contains air pollution records with the following important columns:

| Column | Description |
|------|-------------|
| Data_Value | Pollution measurement value |
| Start_Date | Date when observation was recorded |
| Year | Extracted year from date |
| Month | Extracted month from date |
| Quarter | Quarter of the year |
| Season | Season category |
| Location | City or area where pollution was recorded |
| Indicator_Name | Type of pollutant |

---

## Data Analysis Process

### 1. Data Cleaning
- Removed missing values
- Converted date columns
- Extracted **Year, Month, Quarter**
- Created **Season column**

---

### 2. Exploratory Data Analysis (EDA)

Several charts were created to understand the data:

- Histogram – Distribution of pollution values
- Count Plot – Number of records per season
- Line Plot – Pollution trend over years
- Bar Plot – Average pollution by season and location
- Pair Plot – Relationship between multiple variables
- Correlation Heatmap – Relationship between numerical variables
- Year vs Season Heatmap – Seasonal pollution pattern across years

---

## Key Insights

- Pollution values show a **positively skewed distribution**
- **Winter season has higher pollution levels**
- **Monsoon season has lower pollution levels**
- Pollution levels **fluctuate across years**
- Some **locations show significantly higher pollution**
- Pollution patterns vary by **indicator type**

---

## Power BI Dashboard

An interactive dashboard was created using **Power BI** with the following features:

- Pollution trend by year
- Top polluted locations
- Pollution levels by indicator
- Region and year filters
- Key metrics such as:
  - Total observations
  - Average pollution level
  - Total cities monitored

---

## Types of Analysis Performed

1. **Descriptive Analysis** – Understanding historical pollution patterns  
2. **Diagnostic Analysis** – Identifying reasons for pollution variations  
3. **Predictive Analysis** – Observing trends to estimate future patterns  
4. **Prescriptive Analysis** – Suggesting actions to reduce pollution  

---

## Conclusion

The analysis shows that **pollution levels vary across seasons, locations, and pollutant types**.  

Winter consistently experiences higher pollution levels, while monsoon seasons tend to have lower pollution due to rainfall.

These insights can help authorities focus on **high-risk seasons and locations to implement better pollution control strategies**.

---

## Future Improvements

- Apply **machine learning models** for pollution prediction
- Include **weather data such as temperature and rainfall**
- Build a **real-time monitoring dashboard**
