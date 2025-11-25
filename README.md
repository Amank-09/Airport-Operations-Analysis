# ✈️ Airport Operations Analysis (SQL & Python)

This project analyzes **airport operational data** using SQL and Python to uncover insights related to:
- Passenger trends  
- Flight frequency  
- Seat utilization  
- Route performance  
- Seasonal behavior  
- Airport traffic patterns  
- Longest/shortest routes  
- Year-over-year demand changes  
---

## 📌 Project Overview

Airlines face challenges such as fluctuating passenger demand, inconsistent route performance, capacity underutilization, and seasonal imbalances.  
This project analyzes operational data to answer:
- Which routes perform best?  
- Where do we lose capacity?  
- How do seasonal trends affect demand?  
- Which airports contribute most to overall traffic?  
- What routes show growth or decline year-over-year?  

The objective is to help airlines improve:
- Route planning  
- Seat utilization  
- Resource allocation  
- Scheduling decisions  
- Strategic expansion 
The goal is to provide **actionable insights** for improving operational efficiency, resource allocation, and strategic planning for airlines and airports.

---

## 📊 Features & Analysis Covered

1. Total passengers per route  
2. Average seat utilization  
3. Top 5 busiest routes  
4. Flights & passengers per origin city  
5. Total distance flown per airport  
6. Monthly & yearly performance  
7. Underutilized routes (Passenger-to-seat ratio < 0.5)  
8. Top 3 busiest origin airports  
9. Cities contributing most traffic to Bend, OR  
10. Longest flight route by distance
11. Most & least busy months  
12. YOY passenger growth per route   

---

## 🐍 Python Files (ETL + Dashboards + Notebook)

### Included Notebooks:
- **DBConnect.ipynb** – Database connection & environment setup  
- **DBInsert.ipynb** – Data insertion pipeline  
- **AirportProject.ipynb** – Data cleaning + exploration + visualizations  
- **EmployeeDash.ipynb** – Dashboard logic 

These notebooks handle:
- Loading datasets  
- Connecting to MySQL  
- Cleaning & preprocessing  
- Running SQL queries  
- Generating visual insights & charts  

---

## 🛠️ How to Run the Project

### **1️⃣ Setup Database**
```sql
CREATE DATABASE airport_db;
USE airport_db;

2️⃣ Insert Data
Run DBInsert.ipynb to load dataset into MySQL.

3️⃣ Execute SQL Queries
Use:

MySQL Workbench / DBeaver / VS Code

Run both SQL files in order.

4️⃣ Visualize in Python
Open:

bash
Copy code
jupyter notebook
Run:

AirportProject.ipynb

EmployeeDash.ipynb

This regenerates outputs & graphs automatically.

---

📌 Key Insights Generated (Summary)

- Identified peak and off-peak months for air travel

- Found underperforming routes with low utilization

- Determined longest & busiest routes

- Analyzed city-to-city travel patterns

- Uncovered YOY growth & decline trends

- Identified high-performance airports

- Generated data storytelling for airline strategy

---

**This project provides a complete operational view to enable data-driven airline strategies.**

# Author
**Aman Kushwaha**
*Data Engineer | SQL | Python | Machine Learning*

⭐ If you found this useful, consider giving the repository a star!



