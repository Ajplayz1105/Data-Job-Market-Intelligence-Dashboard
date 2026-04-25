# 📊 Data Jobs Dashboard 1.0 — Power BI

An interactive **Power BI** dashboard visualizing **479,000+ real-world data job postings** — built to explore salary trends, job volume over time, and role-by-role comparisons across the data industry, complete with a drill-through page for deep-diving into any specific job title.

---


## 📁 File

| File | Description |
|------|-------------|
| `Data_Job_Dashboard.pbix` | Power BI Dashboard v1.0 |

---

## ✨ Features

### 📌 KPI Cards
- **Job Count** — 479K total postings analyzed
- **Salary Star Rating** — Overall market quality indicator (★★★☆☆)
- **Median Yearly Salary** — $113K
- **Median Hourly Salary** — $47.62

### 📅 Job Over Time (Line Chart)
Tracks monthly job posting volume across the full year — useful for spotting hiring peaks and slow seasons in the data job market.

### 📍 Hourly vs Yearly Salary Scatter Plot
Plots every job title across both salary dimensions simultaneously — making it easy to identify which roles offer the best value on both an hourly and yearly basis.

### 📊 Job Counts Bar Chart
Horizontal bar chart ranking data roles by total job postings, from Data Engineer at the top down to Software Engineer.

### 🗃️ Summary Table
A clean reference table listing each job title alongside:
- Job Count
- Median Yearly Salary (USD)
- Median Hourly Salary (USD)

### 🔍 Drill-Through — Job Title Detail Page
Click any job title to navigate into a full breakdown page:

| Section | Details |
|---------|---------|
| **Salary Gauges** | Min, median, and max — both yearly and hourly |
| **WFH %** | % of postings offering work from home |
| **No Degree Mention %** | % of postings that don't require a degree |
| **Health Insurance %** | % of postings offering health insurance |
| **Global Jobs Map** | Bing Maps visual of worldwide job locations |
| **Platform Breakdown** | Which platforms post the most jobs (LinkedIn, BeBee, Indeed…) |
| **Job Type Distribution** | Full-time vs Contractor vs Internship split |

---

## 📈 Key Insights

### 💼 Market Overview
- **479K** total data job postings analyzed
- **Median yearly salary: $113K** | **Median hourly: $47.62**

### 💰 Top Paying Roles (from Summary Table)
| Role | Job Count | Median Yearly | Median Hourly |
|------|-----------|--------------|--------------|
| Machine Learning Engineer | 13K | $155K | — |
| Software Engineer | 23K | $145K | — |
| Senior Data Engineer | 31K | $147K | — |
| Data Engineer | 88K | $125K | — |
| Data Scientist | 38K | $125K | — |
| Business Analyst | 29K | $95K | — |
| Data Analyst | 113K | $90K | — |

### 🔍 Data Scientist — Drill-Through Snapshot
- **Median Yearly Salary:** $132K | Range: $18K – $920K
- **Median Hourly:** $49 | Range: $9 – $250
- **Work From Home:** 14% of postings
- **No Degree Mentioned:** 14% of postings
- **Health Insurance Offered:** 14% of postings
- **Job Type:** 91% Full-time
- **Top Platform:** via LinkedIn

---

## 🛠️ Tools & Technologies

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoft&logoColor=white)
![Bing Maps](https://img.shields.io/badge/Bing%20Maps-008373?style=for-the-badge&logo=microsoft&logoColor=white)

- **Power BI Desktop** — Report design and data modeling
- **DAX** — Custom measures for median salary, star rating, and KPI calculations
- **Power Query** — Data transformation and cleaning
- **Bing Maps Visual** — Geographic job distribution
- **Drill-Through Pages** — Role-level deep-dive navigation

---

## 🚀 How to Use

1. **Download** `Data_Job_Dashboard.pbix` from this repository
2. Open with **Power BI Desktop** (free from Microsoft)
3. Use the **Select Job Title** dropdown slicer to filter all visuals
4. Click **"Drill Through To Job Title"** to open the detail page for any selected role
5. Use the **← back arrow** on the drill-through page to return to the main dashboard

---

## 📚 What I Learned

- Building **multi-page Power BI reports** with drill-through navigation
- Writing **DAX measures** for median salary, star ratings, and conditional KPIs
- Designing a clean **light-themed** dashboard with a consistent card-based layout
- Visualizing geographic data with **Bing Maps**
- Using **scatter plots** to compare roles across two salary dimensions at once

---

> *This is version 1.0. An enhanced follow-up (v2.0) with skill-level analysis and country filtering is available in the [Data Jobs Dashboard 2.0](../data-jobs-dashboard-2.0/) project.*
