# 🧠 PySpark Pipelines – Real-World Data Engineering Projects

This repository contains a collection of end-to-end **ETL and analytics pipelines** built using **PySpark**, **Delta Lake**, and **Spark SQL**. Each project simulates real-world use cases commonly found in Data Engineering roles.

## 🔧 Tech Stack

- 🐍 PySpark (DataFrame API)
- 💾 Delta Lake
- 📊 Spark SQL
- 📍 Databricks environment (local or cloud)
- 🗂️ Structured project folders with clean, modular code

---

## 📁 Projects Included

| Project | Description |
|--------|-------------|
| [Sales Analytics ETL](./sales-analytics-etl) | Cleaned sales and product data to analyze monthly revenue and top products |
| [Customer Retention](./customer-retention-etl) | Used transaction history to label customer churn risk and retention activity |
| [Log Analytics](./log-analytics-etl) | Parsed logs to identify module-level errors and track warnings by date |
| [Product Reviews Cleaner](./product-reviews-etl) | Cleaned customer reviews and analyzed product sentiment and user activity |
| [COVID Case Rate Analysis](./covid-etl) | Combined case and population data to compute per capita infection rates |

---

## 📦 Output Format

All final datasets are saved in **Delta Lake format** in the Databricks FileStore (`dbfs:/mnt/data/...`), making them ready for:
- BI tools like Power BI / QuickSight
- Further downstream processing
- Efficient storage and time travel

---

## 💼 Use Case

This repo is designed as a **portfolio showcase for Data Engineering interviews**, proving proficiency in:
- PySpark transformations
- Joins, filters, aggregations, window functions
- ETL pipeline structuring
- Writing clean, production-ready code

---

## 🧠 Author

👨‍💻 **Kaushal Parmar**  
💼 Data Engineer | PySpark | SQL | Delta Lake | AWS  
📫 [LinkedIn](https://www.linkedin.com/in/kaushal-parmar1999/)  
📁 GitHub: [KaushalParmar29](https://github.com/KaushalParmar29)

---

## 📝 License

This repo is open-source and free to use for educational or demonstration purposes.
