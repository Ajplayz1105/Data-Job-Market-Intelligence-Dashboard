# 📊 Data Analytics Portfolio

> **Transforming raw data into visual stories that drive smarter decisions.**  
> A Power BI portfolio exploring the global data job market through interactive dashboards, salary benchmarking, and skill demand analysis.

---

## 🗂️ Projects

| # | Project | Tools | Focus |
|---|---------|-------|-------|
| 1 | [Data Jobs Dashboard 1.0](#1-data-jobs-dashboard-10) | Power BI · DAX · Bing Maps | Salary trends, job volume over time, drill-through role details |
| 2 | [Data Jobs Dashboard 2.0](#2-data-jobs-dashboard-20) | Power BI · DAX | Top skills ranking, salary by role, country-level filtering |

---

## 1. Data Jobs Dashboard 1.0

📁 [`/data-jobs-dashboard`](./data-jobs-dashboard)

The foundational dashboard — a **light-themed Power BI report** that visualizes 479K+ data job postings with a focus on salary trends, job counts over time, and role-by-role comparisons. Includes a **drill-through page** that breaks down any job title into salary ranges, WFH %, degree requirements, global job locations, platform sources, and job type distribution.

**Highlights:**
- 📅 Monthly job posting trends throughout the year
- 📍 Hourly vs yearly salary scatter plot across all data roles
- 🗃️ Summary table — job count + median salaries per role
- 🔍 Drill-through detail page for any job title (e.g. Data Scientist: $132K median, 91% full-time)

➡️ [View Full README](./data-jobs-dashboard/README.md)

---

## 2. Data Jobs Dashboard 2.0

📁 [`/data-jobs-dashboard-2.0`](./data-jobs-dashboard-2.0)

The upgraded dashboard — rebuilt with a **dark theme** and expanded to answer the question: *"Which skills should you learn and which roles pay the most?"* Features toggle-based chart views and a global country slicer, making it easy to explore skill demand and salary benchmarks by role and region.

**Highlights:**
- 🔧 Top 15 in-demand skills ranked by job count (Python leads at ~250K)
- 💰 Top paying roles by median hourly and yearly salary
- 🌍 Country-level slicer for regional analysis
- 🔁 Toggle between Job % / Job Count and Yearly / Hourly salary views

➡️ [View Full README](./data-jobs-dashboard-2.0/README.md)

---

## 📸 Dashboard Previews

### Data Jobs Dashboard 1.0
![Dashboard v1](./data-jobs-dashboard/screenshots/dashboard_v1.png)

### Data Jobs Dashboard 2.0
![Dashboard v2](./data-jobs-dashboard-2.0/screenshots/dashboard_v2.png)

### Drill-Through — Job Title Detail
![Drill Through](./data-jobs-dashboard/screenshots/drill_through.png)

---

## 🛠️ Tech Stack

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoft&logoColor=white)
![Bing Maps](https://img.shields.io/badge/Bing%20Maps-008373?style=for-the-badge&logo=microsoft&logoColor=white)

---

## 📌 Key Takeaways Across Both Dashboards

1. **Python and SQL** dominate — they appear in the most job postings by far
2. **Cloud skills (AWS, Azure)** rank 3rd and 4th — increasingly non-negotiable for data roles
3. **Machine Learning Engineers** earn the highest median hourly salary (~$60/hr)
4. **Data Analysts** are the most numerous role (113K postings) but sit at the lower salary end
5. **91%+ of data roles are full-time** — the market strongly favors permanent employment
6. Upgrading from analyst → engineer → ML engineer has a clear, measurable salary impact

---

## 📂 Repository Structure

```
data-analytics-portfolio/
│
├── README.md                              ← You are here
│
├── data-jobs-dashboard/
│   ├── README.md
│   ├── Data_Job_Dashboard.pbix
│   └── screenshots/
│       ├── dashboard_v1.png
│       └── drill_through.png
│
└── data-jobs-dashboard-2.0/
    ├── README.md
    ├── Data_Job_Dashboard_2_0.pbix
    └── screenshots/
        └── dashboard_v2.png
```

---

## 👤 About

Built by a data enthusiast passionate about turning job market data into visual, actionable insights.  
Feel free to explore, fork, or connect!

[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github)](https://github.com/YOUR_USERNAME)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/YOUR_PROFILE)
