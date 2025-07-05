# Log Analytics ETL Pipeline

This PySpark project processes system logs from a JSON file to summarize error and warning activity across modules.

## ✅ Steps Performed

- Loaded logs from a JSON file
- Parsed timestamp and extracted date
- Filtered for `ERROR` and `WARN` logs
- Aggregated:
  - Count of logs per module
  - Count of logs per day and level

## 🔧 Technologies Used

- PySpark
- Delta Lake
- Spark SQL
- Databricks

## 💾 Output

Processed Delta Tables:
- `/mnt/data/logs_by_module`
- `/mnt/data/logs_by_day_level`

