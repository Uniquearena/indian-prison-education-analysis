# Indian Prison Education & Rehabilitation Analysis (2013)

A data analytics project analyzing educational and vocational training programs across state and union territory prisons in India using 2013 National Crime Records Bureau (NCRB) data.

## 📌 Project Overview

This repository processes and analyzes prison inmate educational enrollment data across 35 Indian States and Union Territories for the year 2013. The focus is on measuring inmate participation across four key educational domains:

- **Elementary Education**
- **Adult Education**
- **Higher Education**
- **Computer Literacy Courses**

The project calculates state-by-state totals, identifies top-performing regions, and aggregates national benchmarks.

---

## 📊 Dataset Summary (2013)

| Educational Category | Total Inmates Benefited |
| :--- | :--- |
| **Elementary Education** | 37,027 |
| **Adult Education** | 53,720 |
| **Higher Education** | 8,311 |
| **Computer Courses** | 7,356 |
| **Grand Total** | **106,414** |

---

## 🛠️ Features & Data Processing

- **Data Aggregation**: Automated calculation of state-wise total beneficiaries using `pandas`.
- **National Benchmark Calculation**: Appends a consolidated `Total` summary row for cross-sectional analysis.
- **Categorical Breakdown**: Measures enrollment patterns across basic literacy vs. higher technical education.

---

## 🚀 Quick Start

### Prerequisites

Ensure you have Python installed along with the required libraries:

```bash
pip install pandas numpy
