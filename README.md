# 🥗 The Nutrition Paradox  
### Global Obesity & Malnutrition Analysis (2012–2022)

---

## 📌 Overview

The **Nutrition Paradox** describes the coexistence of rising obesity and persistent malnutrition across the globe — sometimes within the same country.

This project explores global health data to uncover:

- Long-term obesity trends  
- Malnutrition patterns across regions  
- Gender and age disparities  
- Countries experiencing the "double burden"  
- Data reliability using confidence interval analysis  

The objective is to transform raw health data into meaningful public health insights using SQL, Python, and Power BI.

---

## 🎯 Project Objectives

- Analyze global obesity trends (2000–2022)
- Identify top countries with highest obesity levels
- Examine malnutrition patterns by region
- Compare gender-based disparities
- Detect countries where obesity is rising while malnutrition declines
- Evaluate estimate reliability using CI_Width
- Perform region-wise and age-wise comparative analysis

---

## 🗂️ Datasets Used

### 1️⃣ Obesity Dataset
- Country  
- Region  
- Year  
- Gender  
- Age Group  
- MeanEstimate  
- CI_Width  

### 2️⃣ Malnutrition Dataset
- Country  
- Region  
- Year  
- Gender  
- Age Group  
- MeanEstimate  
- CI_Width  

Both datasets were cleaned, validated, and analyzed for trend consistency and statistical reliability.

---

## 🛠️ Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **SQL** (Aggregation, Trend Analysis, Filtering, HAVING clauses)
- **Power BI** (Interactive Dashboard & Visual Analytics)
- **Jupyter Notebook**
- **Git & GitHub**

---

## 📊 Key Analysis Performed

### 🔹 Exploratory Data Analysis (EDA)
- Distribution & density plots
- Boxplots by region
- Correlation analysis
- Outlier detection
- Time-series visualization

### 🔹 SQL-Based Insights
- Top 5 regions with highest obesity (2022)
- Countries with increasing malnutrition
- Global average obesity per year
- Gender-based averages
- Age group comparison
- Countries ranked by CI_Width (data reliability)

### 🔹 Combined Analysis
- Obesity vs Malnutrition comparison by country
- Countries where obesity increased & malnutrition decreased
- Africa vs America comparative analysis
- Double burden country identification

---

## 📈 Dashboard Highlights (Power BI)

- 🌍 Global trend line charts  
- 📊 Region-wise side-by-side comparison  
- 👥 Gender gap slope charts  
- ⚖️ Double burden quadrant scatter plot  
- 🚨 Risk segmentation visuals  
- 📉 Stability vs volatility analysis  

The dashboard provides interactive filtering by year, region, gender, and age group.

---

## 🔍 Key Insights

- Several countries show a **nutrition transition**, where obesity rises while malnutrition declines.
- Gender disparities are evident across multiple regions.
- Certain countries display high CI_Width, indicating less reliable health estimates.
- A small group of countries disproportionately contribute to global obesity levels.
- The coexistence of overnutrition and undernutrition highlights complex policy challenges.

---

## 🧠 The Nutrition Paradox Explained

While some regions struggle with obesity driven by lifestyle and urbanization, others continue to battle undernutrition due to economic and food security issues.

In some countries, both conditions exist simultaneously — representing a dual public health burden requiring targeted intervention strategies.

---

## 📁 Project Structure

```
Nutrition-Paradox/
│
├── data/
│   ├── obesity.csv
│   ├── malnutrition.csv
│
├── notebooks/
│   ├── eda_analysis.ipynb
│
├── sql/
│   ├── obesity_queries.sql
│   ├── malnutrition_queries.sql
│
├── powerbi/
│   ├── nutrition_paradox_dashboard.pbix
│
└── README.md
```

---

## 🚀 Future Improvements

- Time-series forecasting models  
- Clustering analysis for country segmentation  
- Population-weighted global averages  
- Web-based interactive dashboard deployment  
- Policy recommendation framework  

---

## 📌 Why This Project Matters

This project demonstrates:

- Strong SQL querying skills  
- Advanced exploratory data analysis  
- Data storytelling with Power BI  
- Statistical reasoning and interpretation  
- End-to-end analytical workflow  

It reflects the ability to convert complex global health data into actionable insights.

---

## 📬 Contact

For questions, feedback, or collaboration opportunities, feel free to connect.

---

⭐ If you found this project insightful, consider giving it a star!
