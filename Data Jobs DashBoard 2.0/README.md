# 📊 Data Jobs Dashboard 2.0 — Power BI

An enhanced **Power BI** dashboard — the upgraded successor to [Data Jobs Dashboard 1.0](../data-jobs-dashboard/) — rebuilt with a sharper focus on **skill demand** and **salary benchmarking**, featuring a dark UI, global country filtering, and toggle-based chart views across **479,000+ data job postings**.

---

## 🖥️ Dashboard Preview

![Data Jobs Dashboard 2.0](./screenshots/dashboard_v2.png)

---

## 📁 File

| File | Description |
|------|-------------|
| `Data_Job_Dashboard_2_0.pbix` | Power BI Dashboard v2.0 |

---

## ✨ Features

### 📌 KPI Cards
- **Job Count** — 479K total postings
- **Skills Per Job** — Average of 4.8 skills required per posting
- **Median Yearly Salary** — $113K
- **Median Hourly Salary** — $48

### 🔧 What Are the Top Skills in Data? (Bar Chart)
A horizontal ranked bar chart showing which technical skills appear most across all data job postings — filterable by job title and country.

| Rank | Skill | Approx. Job Count |
|------|-------|------------------|
| 1 | Python | ~250K |
| 2 | SQL | ~240K |
| 3 | AWS | ~150K |
| 4 | Azure | ~130K |
| 5 | Tableau | ~120K |
| 6 | Spark | ~100K |
| 7 | R | ~90K |
| 8 | Excel | ~80K |
| 9 | Power BI | ~75K |
| 10 | Java | ~70K |

### 💰 What Are the Top Paying Jobs in Data? (Bar Chart)
Horizontal bar chart ranking data roles by median salary — togglable between **Median Yearly** and **Median Hourly** salary views.

| Rank | Role | Median Hourly |
|------|------|--------------|
| 1 | Machine Learning Engineer | ~$60 |
| 2 | Software Engineer | ~$58 |
| 3 | Data Engineer | ~$55 |
| 4 | Senior Data Engineer | ~$53 |
| 5 | Cloud Engineer | ~$52 |
| 6 | Senior Data Scientist | ~$50 |
| 7 | Data Scientist | ~$49 |
| 8 | Business Analyst | ~$45 |
| 9 | Senior Data Analyst | ~$44 |
| 10 | Data Analyst | ~$42 |

### 🔁 Dual Toggle Controls
- **Left chart toggle** — Switch between **Job %** (relative share) and **Job Count** (absolute number) views for skills
- **Right chart toggle** — Switch between **Median Yearly Salary** and **Median Hourly Salary** views for job titles

### 🌍 Global Slicers
- **Select Job Title** — Filter all visuals by a specific data role
- **Select Country** — Filter by country to see region-specific skill demand and salary data
- **Clear Slicers** button — Reset all filters instantly

---

## 📈 Key Insights

### 💼 Market Overview
- **479K** job postings analyzed
- Jobs require an average of **4.8 skills** — showing the multi-skill nature of data roles
- **Median yearly salary: $113K** | **Median hourly: $48**

### 🔧 Skill Takeaways
- **Python and SQL** are the two most demanded skills by a wide margin
- **Cloud platforms (AWS, Azure)** rank 3rd and 4th — essential for modern data roles
- **Spark and Databricks** signal strong demand for big data engineering skills
- Tools like **Tableau, Power BI, and Excel** confirm that BI and reporting skills remain core requirements

### 💰 Salary Takeaways
- **Machine Learning Engineers** earn the highest median hourly rate (~$60/hr)
- **Software Engineers and Data Engineers** closely follow — reflecting the premium on engineering skills in data
- **Data Analysts** sit at the lower end (~$42/hr) — underlining the value of upskilling toward engineering or ML

---

## 🆚 What's New vs Dashboard 1.0

| Feature | v1.0 | v2.0 |
|---------|------|------|
| Theme | Light | Dark |
| Skills Analysis | ❌ | ✅ |
| Skills Per Job KPI | ❌ | ✅ |
| Country Filter | ❌ | ✅ |
| Chart Toggle (% / Count) | ❌ | ✅ |
| Salary Toggle (Yearly / Hourly) | ❌ | ✅ |
| Job Over Time Chart | ✅ | ❌ |
| Scatter Plot | ✅ | ❌ |
| Drill-Through Page | ✅ | ❌ |
| Summary Table | ✅ | ❌ |

---

## 🛠️ Tools & Technologies

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoft&logoColor=white)

- **Power BI Desktop** — Report design and data modeling
- **DAX** — Custom measures for median salary, skill counts, and toggle logic
- **Power Query** — Data transformation and cleaning
- **Bookmarks & Buttons** — Toggle views between chart modes
- **Slicers** — Job title and country-level filtering

---

## 🚀 How to Use

1. **Download** `Data_Job_Dashboard_2_0.pbix` from this repository
2. Open with **Power BI Desktop** (free from Microsoft)
3. Use **Select Job Title** to filter by a specific role
4. Use **Select Country** to filter by region
5. Click **Job % / Job Count** to toggle the skills chart view
6. Click **Median Yearly Salary / Median Hourly Salary** to switch the salary chart view
7. Click **Clear Slicers** to reset all filters

---

## 📚 What I Learned

- Designing a **dark-themed dashboard** with a polished, professional look
- Using **DAX bookmarks and toggle buttons** for dynamic chart switching
- Adding **country-level filtering** with cross-visual slicer interactions
- Comparing skill demand across roles using **ranked bar charts**
- Iterating on an existing dashboard — improving UX, adding new KPIs, and extending analytical scope

---

> *This is version 2.0 — an upgrade built on lessons from [Data Jobs Dashboard 1.0](../data-jobs-dashboard/). Both versions are available in this portfolio.*
