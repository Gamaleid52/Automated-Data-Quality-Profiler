# Automated Data Quality Profiler & Auditor 📊

An automated, enterprise-grade data profiling and quality auditing solution built with Python. This project scans large datasets to uncover anomalies, missing structures, and statistical correlations, exporting an interactive HTML dashboard for data engineers and stakeholders.

## 🎯 Business & Engineering Impact
- **Zero-Code Profiling:** Replaces hours of manual exploratory data analysis (EDA) with a 1-click automated report.
- **Data Quality Auditing:** Instantly detects missing values, duplicate records, high cardinality keys, and multicollinearity.
- **Production Ready:** Easily integrated into data pipelines before feeding data into Machine Learning models or SQL Warehouses.

## 🛠️ Tech Stack & Tools
- **Language:** Python 3.x
- **Core Libraries:** Pandas, YData-Profiling (formerly Pandas-Profiling)
- **Deployment & Output:** Google Colab / Jupyter Notebooks, Interactive HTML Dashboards

## 📈 Sample Preview
The generated interactive dashboard `supermarket_data_quality_report.html` provides:
1. **Dataset Overview:** Total rows/columns, memory footprint, and duplicate rates.
2. **Alerts System:** Automated warnings for highly correlated columns and missing data.
3. **Distribution Graphs:** Built-in Seaborn/Matplotlib visualizations for every single variable.
