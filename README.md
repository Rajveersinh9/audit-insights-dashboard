# 🛡️ Audit Insights Dashboard (Python)

This project analyzes simulated audit log data to uncover risk patterns, frequent control gaps, and potential user-level issues. Built using Python, pandas, and seaborn, it visualizes audit failure trends and generates executive-style insights.

---

## 📊 Project Overview

- Parsed and analyzed structured audit logs from CSV format using `pandas`
- Identified failure hotspots by module, user, and time of day
- Visualized risk patterns using bar charts, line plots, pie charts, and heatmaps
- Generated insights that simulate internal audit review for enterprise control systems

---

## 🧠 Use Case Relevance

This project simulates:
- Enterprise audit log analysis
- Pattern detection across risk dimensions (time, severity, users)
- Data storytelling for audit leadership and strategic risk teams

It aligns with internal audit, compliance, and AI-enhanced governance use cases — as expected in Strategic Risk roles like those at RBC.

---

## 🧰 Tools & Technologies

- Python 3.x  
- pandas  
- seaborn  
- matplotlib  

---

## 🧾 Dataset Description

**File:** `audit_log.csv`  
**Structure:**

| Column     | Description                          |
|------------|--------------------------------------|
| timestamp  | Date and time of the user activity   |
| user_id    | Unique identifier for the user       |
| action     | Action performed                     |
| result     | Success or Failure                   |
| module     | Application module involved          |
| severity   | Severity level (Low/Medium/High)     |
| location   | City or remote access                |

---

## 📊 Key Visualizations

- ❌ **Failures by Module** – Bar chart of where most failures happen  
- 🕒 **Failure Trend by Hour** – Line graph to spot time-based spikes  
- 🎯 **Severity Breakdown** – Pie chart showing distribution of Low/Medium/High risks  
- 🧍 **Top Users by Failures** – Flagging risky user activity  
- 🔥 **Heatmap of Failures by Hour & Module** – High-density risk patterns  

---

## 🚀 How to Run

1. Clone or download this repository  
2. Install the required libraries:

```bash
pip install pandas matplotlib seaborn

