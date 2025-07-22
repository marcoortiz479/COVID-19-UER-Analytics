# 🦠📈📊 COVID-19 and Unemployment Rate Analytics

**Contributors**:
- Marco Ortiz
- Tania Ortiz

---

## 📃 Table of Contents

1. [Project Overview](#-project-overview)
2. [Project Summary](#-project-summary)
3. [Files](#-files)
4. [Tools & Libraries](#-tools-&-libraries)
5. [Key Accomplishments](#-key-accomplishments)
6. [Key Takeaways](#-key-takeaways)
7. [Findings & Insights](#-findings-&-insights)
8. [Future Improvements](#-future-improvements)

---

## 📝🎯 Project Overview & Project Goals

**Project Overview**:
This project investigates the relationship between monthly COVID-19 case counts and unemployment rates from January 2020 to May 2022 across five countries: United States, Brazil, India, France, and Germany.

Deploying Python, Pandas, Seaborn, and Plotly, the analysis visualizes and statistically examines how pandemic waves correlated with labor market disruptions.

**Project Goals**:
- Examine the correlation between rising COVID-19 case numbers and unemployment rates.
- Explore unemployment trends before, during, and after COVID-19 peaks.
- Visualize pandemic impact using interactive subplots and time-series graphs.
- Generate insights to inform post-pandemic labor market recovery discussions.

---

## 📊 Project Summary
- 📁 Dataset Size: 141 rows from 5 countries over 29 months (January 2020 – May 2022)

- 🧮 Columns: Country, Date, New Covid Cases, Unemployment Rate

- 📌 Countries Analyzed:
  - United States: 29 records
  - Brazil: 28 records
  - India: 28 records
  - France: 28 records
  - Germany: 28 records

-   📉 Analysis Scope:
  -   Time-series visualization of COVID-19 and unemployment rate trends per country.
  -   Pearson correlation analysis between monthly case spikes and unemployment rates.
  -   Scatter plots with linear regression for each country to identify patterns and deviations.

---

## 📂 Files

- `COVID-19 and Unemployment Rate Analytics.ipynb`
- `COVID-19 Cases and Unemployment Rates.xlsx`
-  `Plotly COVID-19 Cases.png`
-  `Plotly Pearson Correlation COVID-19 Cases vs. Unemployment Rate.png`
-  `Plotly Unemployment Rate.png`

---

## 🔧 Tools & Libraries

- **Python**: The main programming language deployed in this project.
- **Pandas**: Reading .xlsx file for data manipulation and cleaning.
- **Matplotlib**: Utilized for data visualization to capture supplemental chart formatting such as line charts.
- **Seaborn**: Applied for data visualization based on regression plots.
- **Plotly**: Created for interactive time-series graphs.

---

## 📌 Key Accomplishments

- Cleaned and structured 141 monthly observations from .xlsx format.
- Filtered and segmented data by country to track timeline-specific trends.
- Used Plotly and Seaborn to build both interactive and static charts.
- Calculated Pearson correlation coefficients to quantify relationships.
- Identified weak to moderate correlations between COVID-19 surges and labor market fluctuations.
- Clearly communicated insights using well-annotated graphs and written interpretation.

---

## 🔑 Key Takeaways

- U.S. & India saw steep spikes in unemployment early in the pandemic, followed by gradual recovery.
- Brazil maintained high unemployment throughout the period, regardless of case trends.
- Germany and France demonstrated relatively stable employment, reflecting strong government intervention or economic policies.
- Correlation is country-dependent: Some nations show an inverse relationship between rising case numbers and unemployment, while others show little correlation.

---

## 📈📊 Findings & Insights

- United States: Sharp unemployment spike in April 2020 (~14.7%), weakly correlated with pandemic waves that followed.
- India: Higher unemployment rates aligned more closely with pandemic peaks, particularly in mid-2021.
- Germany & France: Less pronounced unemployment changes, possibly due to social welfare programs.
- Brazil: Correlation between COVID-19 cases and unemployment rate for Brazil was moderately positive, indicating that pandemic intensity and job losses were somewhat aligned.

---

## 🔮 Future Improvements

- Incorporate vaccination rates, lockdown stringency indexes, or economic stimulus data
- Expand timeline beyond 2022 to capture post-pandemic recovery
- Use machine learning models to forecast unemployment based on pandemic-related variables
- Deploy interactive dashboard via Streamlit or Dash
