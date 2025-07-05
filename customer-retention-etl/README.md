# Customer Retention ETL Pipeline

This PySpark project labels customers based on their transaction activity and identifies retention patterns.

## ✅ Steps

- Loaded `customers.csv` and `transactions.csv`
- Calculated last transaction date per customer
- Derived days since last transaction
- Labeled customer as:
  - Active (≤30 days)
  - Dormant (31–180 days)
  - Churn Risk (>180 days)
- Aggregated monthly active users

## 💾 Output

Delta tables:
- `/mnt/data/customer_status`
- `/mnt/data/monthly_active_users`

