# 🚲 Cyclistic Bike-Share Analysis

## 📌 Project Overview

This project is a data analytics case study based on Cyclistic, a fictional bike-share company.

The goal of this analysis is to understand how **casual riders and annual members use Cyclistic bikes differently** and use these insights to recommend strategies that could help convert casual riders into annual members.

This project was completed as part of the **Google Data Analytics Certificate Capstone Project**.

---

## 🎯 Business Task

**How do annual members and casual riders use Cyclistic bikes differently?**

Cyclistic wants to understand the differences in riding behavior between casual riders and annual members in order to develop marketing strategies that can encourage casual riders to become annual members.

---

## 📊 Dataset

The analysis uses Cyclistic historical bike-trip data covering the **last 12 months**.

The dataset contains approximately **6 million ride records** and **13 columns**.

### Data Preparation & Cleaning

The following steps were performed during the data preparation and cleaning process:

- Checked the dataset for missing values
- Created a `ride_length` column
- Calculated ride length using `ended_at - started_at`
- Identified rides with negative ride lengths
- Investigated invalid records where the ending time occurred before the starting time
- Removed invalid negative ride-length records
- Prepared the data for further analysis and visualization

---

## 🛠️ Tools Used

- **Python** — Data preparation and analysis
- **Power BI** — Data visualization and dashboard creation
- **GitHub** — Project documentation and portfolio

---

## 🔍 Analysis

The analysis compares casual riders and annual members based on:

- Total number of rides
- Average ride length
- Average ride length by day of the week
- Monthly ride patterns
- Overall riding behavior

---

## 💡 Key Findings

### 1. Casual riders have longer average rides

Casual riders have a higher average ride length than annual members.

- **Casual riders:** 21.2 minutes
- **Annual members:** 12.4 minutes

Although casual riders take fewer rides overall, their individual rides tend to be longer.

---

### 2. Annual members take more rides

Annual members took significantly more rides than casual riders.

- **Annual members:** 3.89 million rides
- **Casual riders:** 2.15 million rides

The difference is approximately **1.74 million rides**.

---

### 3. Different riding behavior

Overall, annual members use Cyclistic more frequently, while casual riders tend to take longer rides.

This shows a clear difference in usage behavior between the two rider groups.

---

### 4. Possible difference in trip purpose

The observed pattern may suggest that annual members use Cyclistic more regularly, while casual riders may use the service more occasionally or recreationally.

However, the available data does not directly provide information about occupation, tourism, or trip purpose, so this is only a possible explanation and would require additional data to confirm.

---

### 5. Weekend riding patterns

Casual riders generally have longer average ride lengths on weekends.

Sunday has the highest average ride length for casual riders at approximately **24.9 minutes**.

This suggests that casual riders may use Cyclistic differently on weekends compared with regular members.

---

## 📈 Power BI Dashboard

The analysis was visualized using Power BI.

The dashboard includes:

- Average ride length comparison
- Total ride comparison
- Average ride length by day
- Monthly ride trends
- Casual vs. member comparisons

---

## 💼 Business Recommendations

Based on the analysis, the following recommendations could help Cyclistic encourage casual riders to become annual members.

### 1. Target longer-trip casual riders

Cyclistic should target casual riders who take longer rides with targeted membership promotions and incentives.

### 2. Highlight the value of annual membership

Cyclistic should clearly communicate the benefits and value of annual membership to casual riders who use the service repeatedly.

### 3. Focus marketing campaigns on weekends

Cyclistic should consider running membership-focused promotions during weekends, when casual riders tend to have longer rides.

---

## 🎯 Skills Demonstrated

- Data Cleaning
- Data Preparation
- Exploratory Data Analysis
- Python
- Power BI
- Data Visualization
- Business Analysis
- Insight Generation
- Data Storytelling
- Business Recommendations

---

## 📁 Project Files

This repository contains the following project materials:

- 📊 Power BI dashboard
- 📑 Case study presentation
- 📖 Project documentation

---

## 📝 Conclusion

The analysis shows a clear difference between casual riders and annual members.

**Annual members take more rides, while casual riders tend to have longer rides.**

These differences in riding behavior can help Cyclistic develop targeted marketing strategies aimed at encouraging casual riders to become annual members.

---

## ⚠️ Disclaimer

Cyclistic is a fictional company used for this case study. This project was completed for educational and portfolio purposes as part of the **Google Data Analytics Certificate**.
