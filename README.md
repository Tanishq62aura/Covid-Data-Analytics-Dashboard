# 📊 COVID-19 Cases Analytics Dashboard | Power BI

A comprehensive **Power BI Dashboard** developed to analyze global COVID-19 data through interactive visualizations, KPIs, and country-wise insights. This dashboard enables users to monitor confirmed cases, deaths, recoveries, and mortality rates over time.

---

## 📌 Project Overview

This project provides an interactive dashboard built in **Microsoft Power BI** using COVID-19 datasets. The dashboard helps users understand the spread of COVID-19 across different countries and time periods through dynamic charts, slicers, and KPI cards.

---

## ✨ Features

- 📈 Interactive trend analysis of COVID-19 cases
- 🌍 Country-wise comparison of Confirmed, Death, and Recovery cases
- 📅 Month-based filtering using slicers
- 📊 Dynamic KPI cards
- 📉 Active cases trend analysis
- 📋 Detailed country-level data table
- 📌 Mortality rate calculation
- 🎨 Dark-themed professional dashboard design

---

# 📸 Dashboard Preview

## Dashboard Overview


<img width="1280" height="725" alt="image" src="https://github.com/user-attachments/assets/df19965a-6e42-444b-a887-d896732a4cb0" />

---

## Trends & Monthly Analysis

<img width="1280" height="722" alt="image" src="https://github.com/user-attachments/assets/e1a8bc2e-c071-4c04-b2b0-5e0aba70b808" />


---

## Country-wise Analysis

<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/d1a466d8-11c8-4d51-940d-b4f394967e3b" />


> **Note:** Create an **images** folder inside your repository and place the screenshots with the above names.

---

# 📊 Dashboard Pages

## Page 1 - Executive Summary

Contains:

- Total Confirmed Cases
- Total Death Cases
- Total Recovered Cases
- Mortality Rate
- Confirmed Cases by Country
- Confirmed Cases Trend by Date
- Percentage of Global Confirmed Cases

---

## Page 2 - Trend Analysis

Contains:

- Month Number Slicer
- Confirmed, Death & Recovery Trend
- Active Cases Trend
- Monthly Confirmed Cases
- Interactive Filtering

---

## Page 3 - Country Analysis

Contains:

- Top Countries by Confirmed Cases
- Top Countries by Death Cases
- Detailed Country-wise Data Table
- Mortality Rate Comparison

---

# 📈 Key Performance Indicators (KPIs)

| KPI | Description |
|------|-------------|
| Total Confirmed | Total number of confirmed COVID-19 cases |
| Total Deaths | Total recorded deaths |
| Total Recovered | Total recovered patients |
| Mortality Rate | Deaths / Confirmed Cases |

---

# 📂 Dataset Information

The dashboard is built using a COVID-19 dataset containing:

- Country/Region
- Date
- Confirmed Cases
- Death Cases
- Recovered Cases
- Active Cases
- Month Number

---

# 🛠 Tools & Technologies

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Interactive Visualizations

---

# 📊 Visualizations Used

- KPI Cards
- Line Charts
- Area Charts
- Clustered Bar Charts
- Tables
- Slicers
- Filters

---

# 📐 DAX Measures Used

Examples of measures used in the dashboard:

```DAX
Total Confirmed = SUM(Covid[Confirmed])

Total Deaths = SUM(Covid[Deaths])

Total Recovered = SUM(Covid[Recovered])

Active Cases =
SUM(Covid[Confirmed])
- SUM(Covid[Deaths])
- SUM(Covid[Recovered])

Mortality Rate =
DIVIDE(
    SUM(Covid[Deaths]),
    SUM(Covid[Confirmed]),
    0
)
```

---

# 🎯 Insights

- The United States recorded the highest number of confirmed cases.
- Brazil and Russia were among the top affected countries.
- Recovery cases increased steadily throughout the observed period.
- Active cases experienced rapid growth during peak months.
- Mortality rate remained relatively low compared to total confirmed cases.

---

```

---

# 🚀 How to Use

1. Clone this repository.

```bash
git clone https://github.com/yourusername/COVID-19-PowerBI-Dashboard.git
```

2. Open the `.pbix` file using **Power BI Desktop**.

3. Refresh the dataset if required.

4. Explore the dashboard using filters and slicers.

---

# 🎓 Learning Outcomes

This project demonstrates practical knowledge of:

- Data Cleaning
- Data Modeling
- Power Query
- DAX Calculations
- Dashboard Design
- Data Visualization
- Interactive Reporting

---

# 📌 Future Improvements

- Real-time API integration
- Global map visualization
- Vaccination analysis
- Forecasting using Power BI
- Drill-through reports
- Mobile optimized dashboard

---

# 👨‍💻 Author

**Tanishq**

B.Tech (Cyber Security)

Learning:
- Python
- Data Analytics
- Power BI
- SQL
- Data Science

---

## ⭐ If you found this project useful, consider giving it a Star on GitHub!
