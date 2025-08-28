# Formula 1 Historical Analysis – Data Science & Machine Learning Project

This was my **first project** for the Data Science & Machine Learning course. The goal was to choose a dataset, perform an **ETL process**, conduct an **exploratory data analysis (EDA)**, and simulate a real-world scenario by creating guiding questions for the analysis.

---

## 🎯 Objectives

- Perform a complete ETL process to merge multiple CSV files into a single consolidated DataFrame.
- Explore historical Formula 1 data to identify patterns and trends.
- Analyze performance metrics for drivers and teams across decades.
- Create visualizations that support data-driven insights and recommendations.
- Simulate a real-world business scenario with actionable conclusions.

---

## 📄 Dataset Overview

The data comes from [Kaggle: Formula 1 World Championship (1950–2020)](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020). The project uses the following CSV files:

- `drivers` → Detailed information about drivers.  
- `races` → Calendar of races with location and date.  
- `results` → Race results for each driver in each Grand Prix.  
- `circuits` → Information about the circuits where races were held.  
- `constructors` → Information about the participating teams (constructors).  

These datasets were merged and cleaned to create a **single DataFrame** that was used for all subsequent analysis.

---

## ✅ Analysis

The project includes:

- **Data Cleaning and Preparation:** Handling missing values, merging driver names and constructor names, and standardizing columns.  
- **Exploratory Data Analysis (EDA):**  
  - Top drivers and constructors by world championships.  
  - Team performance across decades using percentage of points per season.  
  - Scatter plots showing consistency, dominance, and historical performance of teams.  
- **Visualization:**  
  - Pie charts of the top 5 teams per decade.  
  - Scatter plots of teams showing number of seasons vs. average percentage of points per season.  
- **Real-World Scenario Simulation:**  
  - Analyzing potential sponsorship options based on historical performance and current driver-team combinations.  

---

## 📊 Key Insights

- **Drivers:** Michael Schumacher and Lewis Hamilton lead historically, followed by Juan Manuel Fangio.  
- **Teams:** Ferrari consistently dominates across decades, followed by McLaren, Williams, Mercedes, and Red Bull.  
- **Sponsorship Recommendation:** Red Bull with Max Verstappen is the top option, followed by Ferrari with Hamilton or Leclerc. Carlos Sainz with Williams is not recommended due to low performance.  

---

## ✅ Instructions & Reproducibility

- The project is fully reproducible with Python (pandas, matplotlib, seaborn, numpy).  
- Start by running the ETL to merge the CSVs into a single DataFrame.  
- Perform cleaning, handle missing values, and merge relevant columns.  
- Use the provided functions to generate the pie charts and scatter plots.  
- Interpret the charts to answer the guiding questions and simulate decision-making.

---

This project demonstrates **data engineering, EDA, visualization, and analytical storytelling**, all within a context simulating a real-world scenario for data-driven decision making in sports analytics.
