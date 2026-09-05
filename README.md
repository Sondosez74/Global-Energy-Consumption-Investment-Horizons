# 📊 Global Energy Consumption & Investment Horizons (1965–2021)
> **Executive Dashboard & Market Segmentation Analysis**

---

## 📌 Executive Summary
This project provides a professional, executive-grade business intelligence dashboard designed for **C-level leadership** to evaluate global energy trends. Transforming over **13,670+ raw data points** into actionable investment insights, the analysis employs advanced statistical frameworks to group international markets into strategic tiers and mitigate data skewness.

---

## 📸 Dashboard Preview
![Executive Dashboard](C:\Users\HP\Desktop\New folder (7)/Capture.PNG)  
Capture.PNG
---
## 🎯 Key Features & Business Logic

* 🎛️ **Dynamic Interactivity:** Integrated unified global Slicers across all KPI cards and visualization charts for real-time filtering by **Year** and **Country**.
* ⚖️ **Skewness Mitigation:** Leveraged **Median** statistics over traditional Mean metrics to establish a reliable investment baseline, eliminating distortions from top-tier energy consumers.
* 📈 **4-Tier Market Segmentation:** Applied Interquartile Range ($IQR$) and $Z\text{-Score}$ methodologies to divide global energy markets into distinct operational scopes.
* 🛡️ **Fault-Tolerant Analytics:** Optimized complex Google Sheets formulas using `FILTER` and `IFERROR` logic to handle empty cells and non-numeric entries dynamically.

---

## 📐 Statistical Framework & Market Tiers

| Market Tier | Statistical Criteria | Business Focus & Strategic Horizon |
| :--- | :--- | :--- |
| 🟢 **Low Demand Tier** | Below $Q1$ ($< 2,815.51$) | Emerging & low-volume consumption markets |
| 🔵 **Core Target Market** | Within $IQR$ ($2,815.51 - 35,183.46$) | Primary safe-investment baseline (Median focus) |
| 🟡 **High Growth Tier** | Upper $IQR$ to Outlier Boundary | Rapidly expanding demand markets |
| 🔴 **Outliers / Premium Tier** | $> Upper Boundary$ ($> 83,735.39$) | High-demand mega markets (Top consumers) |

---

## 📊 Key Calculated Metrics

```text
  ├── 📉 First Quartile (Q1)     : 2,815.51
  ├── 📈 Third Quartile (Q3)    : 35,183.46
  ├── 📊 Interquartile Range     : 32,367.95 (IQR)
  ├── 🚨 Upper Outlier Limit     : 83,735.39
  ├── 🌐 Global Mean             : 25,053.94
  └── 📏 Standard Deviation      : 37,778.97 (Std Dev)

🛠️ Tools & Technologies Used
🟩 Platform: Google Sheets / Microsoft Excel

🧮 Advanced Formulas: MEDIAN, FILTER, ISNUMBER, IFERROR, AVERAGEIFS, Z-Score

🎨 Visualizations: Bar/Column Charts, Diverging Scale Indicators, Dynamic Slicers, Custom Executive Styling

📂 Version Control & Portfolio: Git & GitHub





