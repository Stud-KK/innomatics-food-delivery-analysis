
# Food Delivery Data Analysis – Innomatics Research Labs

This repository contains the Jupyter Notebook submitted for the **Innomatics Research Labs – Advanced GenAI Internship Entrance Test**.

## 📌 Objective
To simulate a real-world data integration and analysis workflow by:
- Loading data from multiple formats (CSV, JSON, SQL)
- Merging datasets using appropriate join keys
- Creating a final consolidated dataset
- Performing analytical queries to answer business-focused questions

## 📂 Datasets Used
- **orders.csv** – Transactional order data
- **users.json** – User master data
- **restaurants.sql** – Restaurant master data

## 🛠 Tools & Technologies
- Python
- Pandas
- SQLite
- Jupyter Notebook (Google Colab)

## 🔗 Key Operations
- Left joins using `user_id` and `restaurant_id`
- Creation of a final merged dataset (`final_df`)
- Analysis of:
  - Order trends
  - User behavior
  - City-wise and cuisine-wise performance
  - Membership impact (Gold vs Regular)
  - Revenue distribution and seasonality

## 📁 File in This Repository
- `food_delivery_analysis.ipynb` – Complete notebook with code, outputs, and explanations

## ✅ Notes
- All analysis is performed using the final merged dataset as the single source of truth.
- Outputs are visible directly in the notebook.

---
