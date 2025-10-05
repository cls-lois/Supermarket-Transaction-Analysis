# Supermarket Transaction Analysis using SQL

## 📊 Project Overview
This project focuses on a financial and logistical **SQL analysis** of supermarket Point-of-Sale (POS) transaction data. The primary objective is to leverage database queries to address critical business questions related to customer behavior, store productivity, and operational efficiency within a retail setting.

The analysis is designed to provide data-driven insights for strategic decisions, such as optimizing opening hours, refining labor scheduling, and understanding key sales drivers.

---

## 🛠️ Project Focus & Specific Data Skills

| Category | Skills Applied |
| :--- | :--- |
| **Project Focus** | **SQL Database Project**, Statistical Analysis, Exploratory Data Analysis (EDA) |
| **Specific Data Skills** | **Time Series** (analyzing date/time trends), Data Storytelling |

---

## 🚀 Key Analysis Areas

The project addresses operational and strategic questions relevant to supermarket management by querying the `pos_operator_logs` and `pos_transactions` data.

### 1. Operational Efficiency & Staffing Analysis
* **Goal:** Determine staffing levels and distribution across different time periods.
* **Methodology:** Utilizing SQL functions like `COUNT(DISTINCT...)` and `DATE_PART()` to count unique operators working per day and week.
* **Key Findings:** Identification of operator counts on specific dates (e.g., Sundays) to assess potential staffing gaps or over-scheduling.

### 2. Business Intelligence & Cost Analysis Foundation
* **Goal:** Set the groundwork for deeper financial and cost-benefit analysis.
* **Insight:** By identifying employee presence, the analysis provides the initial metrics required to calculate **average savings/costs** associated with operational decisions (e.g., staying open on a Sunday).

---

## 📝 SQL Queries & Techniques

The core of this project involves writing robust and efficient SQL queries. Key techniques employed include:

* **Date/Time Manipulation:** Using **`EXTRACT()`** and **`DATE_PART()`** to segment and analyze data based on specific time components (year, week).
* **Data Aggregation:** Employing **`COUNT(DISTINCT...)`** for accurate counting of unique entities (operators).
* **Type Casting:** Casting date/time fields (e.g., `begin_date_time::DATE`) to ensure accurate date-based grouping for time-series analysis.

---
