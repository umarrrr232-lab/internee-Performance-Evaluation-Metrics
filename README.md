# 📊 Internship Analytics Projects
**By Umar | internee.pk Data Analytics Internship**

---

## 🗂️ Projects Overview

This repository contains two data analytics projects completed during my internship at **internee.pk**, built using Python, Pandas, and Matplotlib in Google Colab.

---

## 📁 Project 1 — Internship Completion Rate Analysis

### What it does
Analyzes 8,500+ real learner records to identify key factors behind internship completion and dropout rates.

### Key Findings
- Mentor interaction is the **#1 predictor** of completion
- Internships under 6 weeks have **<50% completion rate**
- **Workload mismatch** is the top dropout reason (34%)
- Engineering & Data Science departments outperform others

### Charts included
- Status breakdown (who completed, who dropped out)
- Completion rate by country (top 10)
- Completion vs dropout by gender
- Monthly signup trend over time
- Top programs by enrollment

### File
```
internship_analysis.py
```

---

## 📁 Project 2 — Intern Performance Tracking System

### What it does
Builds a KPI-based scoring system that combines 4 metrics into one performance score out of 100, then visualizes it across departments and months.

### KPI Formula
```
Performance Score =
    Task Completion  × 30% +
    Quality Score    × 25% +
    Mentor Feedback  × 25% +
    Punctuality      × 20%
```

### Performance Labels
| Score | Label |
|-------|-------|
| 80+   | Excellent |
| 65–79 | Good |
| 50–64 | Average |
| <50   | Needs Improvement |

### Charts included
- Performance category distribution
- Avg score by department
- Monthly performance trend
- Quality vs mentor feedback (scatter)
- Task completion spread (box plot)
- Top 10 performers

### File
```
intern_performance.py
```

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data loading & manipulation |
| Matplotlib | Charts & dashboards |
| Google Colab | Development environment |
| NumPy | Data generation & math |

---

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com)
2. Upload `data.csv` and the `.py` file
3. Copy the code into a cell and run it
4. Dashboard saves as a `.png` file automatically

---

## 👤 Author
**Umar**
Intern @ internee.pk
