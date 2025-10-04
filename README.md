Got it ✅ — I’ll properly **restructure your project description with clean line breaks and indentation**, so when you copy-paste it into GitHub/Word/Resume it looks neat and readable:

---

# 🚲 Cyclistic (Divvy) Bike-Share Case Study

**Google Data Analytics Capstone | RStudio**

---

## 📌 Project Overview

This project is part of the Google Data Analytics Capstone Case Study:
**“How Does a Bike-Share Navigate Speedy Success?”**

Cyclistic (fictional name for Divvy) is a bike-share company in Chicago that wants to convert **casual riders into annual members**.

This analysis answers:

* How do annual members and casual riders use Cyclistic bikes differently?
* What insights can help convert casual riders into members?

The project follows the **Ask → Prepare → Process → Analyze → Share → Act** framework.

---

## 🎯 Business Task

* Identify behavioral differences between casual riders and annual members
* Provide data-driven recommendations to increase memberships

---

## 📂 Data Sources

* Divvy Q1 2019 dataset
* Divvy Q1 2020 dataset
* Publicly available from Divvy Trip Data
* Licensed for public use

---

## 🛠 Tools & Libraries

* **R / RStudio (Posit Cloud)**
* **tidyverse** → data wrangling, cleaning
* **lubridate** → date & time manipulation
* **ggplot2** → visualizations

---

## 🔄 Data Cleaning & Wrangling

✔ Renamed 2019 columns to match 2020 schema
✔ Combined Q1 2019 & Q1 2020 datasets with `bind_rows()`
✔ Re-coded rider types (`Subscriber → member`, `Customer → casual`)
✔ Created new columns: date, month, day, year, day_of_week, ride_length
✔ Calculated ride_length for 2020 data (`ended_at - started_at`)
✔ Removed invalid trips (negative durations, quality-control rides)

---

## 📊 Analysis

* **Summary statistics** → mean, median, max, min ride durations
* **Comparisons** → ride patterns by weekday (member vs. casual)
* **Aggregations** → rides per weekday & average ride duration
* **Visualizations** →

  * 📅 Number of rides by weekday
  * ⏱ Average ride duration by weekday

---

## 📈 Key Insights

* Members ride more frequently than casual riders, especially on weekdays → indicates commuting behavior.
* Casual riders take longer trips, especially on weekends → suggests leisure or tourist use.
* Weekend ridership is dominated by casual users, while members maintain steady weekday usage.

---

## ✅ Recommendations

1. Promote **weekend leisure benefits** of memberships to casual riders.
2. Offer **trial or seasonal memberships** to encourage casual rider conversion.
3. Use **personalized marketing campaigns** showing potential savings for frequent casual riders.

---

## 📊 Supporting Visualizations

* `plots/01_rides_by_weekday_member_vs_casual.png`
* `plots/02_avg_ride_duration_by_weekday.png`

These visualizations support the key findings above.

---

## 📤 Exported Outputs

* `avg_ride_length.csv` → summary dataset for Excel/Tableau
* `plots/` → ggplot visualizations
* `case_study.pdf` → full case study report (problem → process → insights → recommendations)
* `deliverables.pdf` → summary of all outputs, datasets, and visualizations

---

## 📂 Repository Structure

```
cyclistic-bike-share-case-study/
├── cyclistic_analysis.R     # Main R script (data cleaning, wrangling, analysis)
├── avg_ride_length.csv      # Summary CSV for external tools (Excel/Tableau)
├── README.md                # Project overview & instructions
├── plots/                   # ggplot visualizations (PNG/PDF)
├── case_study.pdf           # Main case study report (problem → insights → recommendations)
└── deliverables.pdf         # Deliverables summary (datasets, outputs, visualizations)
```

---

✨ Now everything is **line-wise and properly indented** — perfect for a **README.md** or report.

Do you also want me to make a **shorter README version** (just overview + insights + recommendations) so it looks professional on GitHub?
