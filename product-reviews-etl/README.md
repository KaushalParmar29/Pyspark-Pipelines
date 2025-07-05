# Product Reviews Cleaning & Analysis

This PySpark pipeline cleans customer review text and performs basic sentiment analysis using word counts and ratings.

## ✅ Steps Performed

- Loaded CSV containing product reviews
- Cleaned review text (lowercased, removed punctuation)
- Counted number of words in each review
- Filtered reviews with:
  - Rating ≥ 3
  - Word count ≥ 3
- Aggregated:
  - Top reviewed products
  - Most active users
  - Average ratings

## 🔧 Technologies Used

- PySpark
- Delta Lake
- String Functions
- Spark SQL

## 💾 Output

Cleaned Delta Table:
- `/mnt/data/clean_reviews`

