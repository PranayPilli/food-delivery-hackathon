# Food Delivery Data Analysis Hackathon

## Project Overview
This project integrates and analyzes food delivery data from multiple real-world data formats to build a unified dataset for analytical insights. The final dataset acts as the single source of truth for answering all hackathon questions.

---

## Datasets Used
The following datasets were provided:

- **orders.csv** – Transactional order data  
- **users.json** – User master data  
- **restaurants.sql** – Restaurant master data  

All datasets were combined using LEFT JOINs to ensure no order data was lost.

---

## Tools & Technologies
- Python  
- Pandas  
- SQLite  
- Google Colab  
- Jupyter Notebook  

---

## Data Processing Workflow
1. Loaded CSV, JSON, and SQL datasets into Python  
2. Executed SQL script using SQLite  
3. Merged datasets using Pandas `merge()` function  
4. Cleaned duplicate columns and ensured data consistency  
5. Generated a final consolidated dataset  

---

## Final Output
- **final_food_delivery_dataset.csv**

### Final Dataset Contains:
- Order details  
- User information  
- Restaurant information  

This dataset is the **only source of truth** for all multiple-choice, numerical, and fill-in-the-blank questions in the hackathon.

---

## Analysis Covered
- Order trends over time  
- User behavior patterns  
- City-wise and cuisine-wise performance  
- Membership impact (Gold vs Regular)  
- Revenue distribution and seasonality  

---


