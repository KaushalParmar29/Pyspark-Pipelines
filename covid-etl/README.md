# COVID Case Rate Analysis

This project combines COVID-19 case data with state population to calculate per-capita case rates using PySpark.

## ✅ Steps Performed

- Loaded `covid_cases.csv` and `population.csv`
- Joined datasets on `state`
- Calculated `cases_per_100k = (new_cases / population) * 100000`
- Casted and cleaned all relevant fields

## 🔧 Technologies Used

- PySpark
- Delta Lake
- Joins & Arithmetic Functions

## 💾 Output

Delta Table:
- `/mnt/data/covid_analysis`

