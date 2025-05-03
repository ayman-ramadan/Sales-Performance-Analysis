# 🛒 Sales Performance Analysis

This project focuses on analyzing the sales performance of several shops using ETL processes, data modeling, pivot tables, and interactive dashboards.

---

## 📊 Project Overview

The goal of this project is to empower stakeholders with clear insights to improve business performance using Excel-based tools and dashboards.

---

## 🔄 1. ETL Process

### ✅ Extract
- Collected data from various formats such as `.TXT` and `.XLSX`.

### 🛠️ Transform
- Cleaned data by handling null values, removing duplicates, and fixing formatting issues.
- Merged data from multiple sheets into a single comprehensive dataset containing all yearly records.

### 📥 Load
- Loaded data by creating a data connection only, enabling real-time updates and efficient modeling.

---

## 🧱 2. Data Modeling

- Built a **star schema** by linking dimension tables:
  - `Shipping`, `Customers`, `Date`, and `Products`
- Connected them to the central **fact table**: `Sales`
- Ensured referential integrity and optimized model performance.

---

## 📈 3. Pivot Tables

- Created pivot tables to display key performance indicators (KPIs).
- Answered business-critical questions using metrics like:
  - Total Sales
  - Total Quantity Sold
  - Total Profit

---

## 📊 4. Data Visualization

- Designed an **interactive multi-page dashboard** for business users.
- Used visual components such as:
  - KPI Cards (Total Sales, Quantity, Profit, etc.)
  - Column Charts
  - Pie Charts
  - Bar Charts
  - Map Charts
- Added **slicers** to filter insights by `Year` and `Shipping Mode`.

---
## Dashboard
```markdown
![Alt text](relative/path/to/image.png)
