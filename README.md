# Exploring Socioeconomic Factors and Crime Patterns in New York City

This repository contains a comprehensive analysis of how socioeconomic variables influence violent crime in New York City. Leveraging advanced data processing, visualization, and statistical techniques, the project uncovers spatial and temporal patterns in gunshot incidents and homicides, and examines their relationship with income, unemployment, and insurance coverage.

---

## 📖 Project Overview

Gun violence and homicide remain critical public‑safety challenges in NYC. This project aims to:

- Map and analyze **gunshot incidents** (2006–2022) by ZIP code and borough  
- Track **homicide rates** over time and by neighborhood  
- Examine **income disparities** and their spatial correlation with crime  
- Explore links between **unemployment**, **health insurance coverage**, and violent crime  

Results are presented via interactive Tableau dashboards and static visualizations that inform policymakers, community leaders, and researchers.

---

## 🖥️ Tableau Dashboards

Explore the interactive dashboards on Tableau Public (placeholder link):  
[NYC Crime & Socioeconomic Analysis Dashboard](https://public.tableau.com/app/profile/your_profile_here)

---

## ✨ Features

- **Interactive Maps & Heatmaps**  
  Visualize per‑capita gunshot and homicide rates by ZIP code and borough  
- **Temporal Trend Charts**  
  Year-over-year line graphs of shooting and homicide counts  
- **Scatter & Bubble Plots**  
  Correlate median household income, unemployment rate, and insurance coverage with crime metrics  
- **Drill‑Down Filters**  
  Filter by borough, year, and demographic variables for deep‑dive analysis  
- **Statistical Summaries**  
  Display summary tables and correlation coefficients alongside charts  

---

## 🗂️ Data Sources

| Dataset                                            | Description                                                       | Source URL                                    |
|----------------------------------------------------|-------------------------------------------------------------------|-----------------------------------------------|
| **NYPD Shooting Incident Data (2006–2022)**        | Gunshot event records, location, date/time                        | data.cityofnewyork.us                         |
| **NYPD Homicide Data**                             | Yearly counts of murder incidents by precinct and borough         | data.cityofnewyork.us                         |
| **U.S. Census Economic Characteristics**           | Median household income, poverty rates by ZIP                     | data.census.gov                               |
| **U.S. Census Population Estimates**               | Population counts for per‑capita calculations                     | data.census.gov                               |
| **American Community Survey (ACS) Health Insurance** | Rates of insured vs. uninsured residents by ZIP                   | data.census.gov                               |

---

## 🧮 Methodology

1. **Data Cleaning & Preprocessing**  
   - Remove duplicates, handle missing values  
   - Geocode lat/long to derive ZIP codes with GeoPy  
2. **Normalization**  
   - Compute per‑capita crime rates (per 100,000 residents)  
   - Standardize income and unemployment metrics  
3. **Exploratory Visualization**  
   - Generate bar, line, scatter, and heatmap charts in Python (Matplotlib, Seaborn)  
4. **Statistical Analysis**  
   - Calculate Pearson correlation between crime rates and socioeconomic factors  
   - Conduct simple linear regressions to quantify relationships  
5. **Dashboard Build**  
   - Export cleaned extracts for Tableau  
   - Design interactive dashboards with filters and drill‑through capabilities  

---

## 🔍 Key Findings

- **Spatial Clustering:** Bronx and Brooklyn ZIPs exhibit the highest per‑capita shooting and homicide rates.  
- **Income Correlation:** Negative correlation (r ≈ –0.52) between median household income and gunshot rates.  
- **Unemployment Impact:** Positive correlation (r ≈ 0.65) between borough unemployment spikes and homicide peaks.  
- **Insurance Coverage:** Areas with lower health insurance rates see higher violent crime counts, suggesting access‑to‑care as a social determinant.  

---

## 💡 Recommendations

- **Targeted Community Investment:** Prioritize economic development programs in high‑crime, low‑income neighborhoods.  
- **Job Creation & Training:** Address unemployment in hotspot areas to mitigate factors correlated with violent crime.  
- **Health Access Initiatives:** Expand coverage and outreach in uninsured communities as part of violence‑reduction strategies.  
- **Data‑Driven Policing:** Use GIS maps and dashboards to deploy resources where and when they’ll have greatest impact.  

---

## 🛠️ Tools & Technologies

- **Python**: pandas, NumPy, GeoPy, Matplotlib, Seaborn  
- **Tableau**: Desktop for interactive dashboards  
- **GeoPy**: Geocoding latitude/longitude → ZIP code  
- **Jupyter Notebooks**: Data preprocessing, EDA, statistical analysis  
- **Git & GitHub**: Version control  

---

## 📂 Repository Structure

