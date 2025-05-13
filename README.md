# Python-Final-Project

# 🦠 COVID-19 Global Data Tracker

This project presents a comprehensive data analysis report on global COVID-19 trends using Python. It leverages real-world datasets to explore total cases, deaths, daily new cases, vaccination progress, and country-wise comparisons with clear visualizations and insights.

---

## 📌 Project Objectives

- ✅ Import and clean COVID-19 data from a reliable source
- ✅ Analyze time trends: cases, deaths, and vaccinations
- ✅ Compare metrics across selected countries
- ✅ Visualize trends using charts and maps
- ✅ Present insights in a well-documented Jupyter Notebook

---

## 🗂️ Dataset

- **Source:** [Our World in Data – COVID-19 Dataset](https://github.com/owid/covid-19-data/tree/master/public/data)
- **File Used:** `owid-covid-data.csv`

---

## 🧰 Tools & Technologies

- `Python` (Pandas, NumPy)
- `Jupyter Notebook`
- `Matplotlib` & `Seaborn` (Data Visualization)
- `Plotly Express` (Choropleth Map)
- Optional: `GeoPandas`, `Streamlit` (for dashboarding)

---

## 🗺️ Countries Analyzed

- Kenya 🇰🇪
- United States 🇺🇸
- India 🇮🇳
- South Africa 🇿🇦

---

## 📊 Features & Analysis

### 📌 Data Cleaning
- Converted dates to datetime format
- Handled missing data using `dropna()` and interpolation
- Filtered key countries of interest

### 📌 Exploratory Data Analysis
- Line plots: Total cases & deaths over time
- Bar charts: Top countries by total cases
- Daily new cases comparison
- Calculated death rates

### 📌 Vaccination Analysis
- Cumulative vaccinations over time
- Percentage of vaccinated population
- Optional pie charts for vaccinated vs. unvaccinated

### 🗺️ Choropleth Map (Optional)
- Interactive world map showing total cases and vaccination rates

---

## 📈 Key Insights

- The U.S. had the highest total cases and vaccinations globally.
- India experienced the most volatile trends in new daily cases.
- Vaccination rollout in Kenya was slower compared to global averages.
- Death rates were highest early in the pandemic and declined with vaccine availability.

---

## 📝 Deliverables

- ✅ Jupyter Notebook (`covid19_analysis.ipynb`)
- ✅ Visualizations: Line charts, bar graphs, pie charts, choropleth map
- ✅ Summary of insights in markdown cells
- ✅ Optional export: Notebook as PDF or HTML

---

## 📤 How to Run

1. Clone the repo or download the files
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn plotly
final-project.ipynb

👩‍💻 Author
Pauline Mwangi
