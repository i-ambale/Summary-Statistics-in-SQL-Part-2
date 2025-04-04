# 📊 Filtering and Analyzing a Summary Statistic Report using SQL
© ExploreAI Academy

📝 Overview
This project demonstrates how to filter and analyze summary statistics in a MySQL database using the WHERE and HAVING clauses. It forms part of a broader data exploration on the Access_to_Basic_Services table within the united_nations database.

| ⚠️ Note: This notebook is designed to run on a local machine with access to a MySQL server. It will not run on Google Colab due to database connection limitations.
---
## 🎯 Learning Objectives
By the end of this project, you will:

- Understand how to filter SQL data using the WHERE clause.

- Know how to apply conditions to aggregated results using the HAVING clause.

- Learn how to analyze and derive insights from summary statistics in a structured dataset.

---
## 🛠 Requirements
MySQL Server (e.g. via MySQL Workbench)

Python 3 environment (Anaconda or local setup)

Python packages:

- mysql-connector-python or pymysql

- sqlalchemy (if using ORM or pandas)

- pandas (for optional data manipulation)
---
## 🗃️ Dataset
The analysis focuses on the Access_to_Basic_Services table located in the united_nations database. Ensure this database is created and populated before running the notebook.
---
## 🔌 Connecting to the Database
We use Python libraries like mysql.connector or pymysql to connect to the MySQL server. Make sure your credentials are correct and the database is hosted locally.
```
%sql mysql+pymysql://root:password@localhost:3306/united_nations
```
---
## 📈 Key Concepts
- WHERE Clause: Filters rows before aggregation.

- HAVING Clause: Filters groups after aggregation.

- Combining both clauses to create powerful, meaningful reports.
---
## 🚀 How to Run
1. Clone the repository:
```sql
git clone https://github.com/your-username/sql-summary-analysis.git
cd sql-summary-analysis
```
2. Open the notebook in Jupyter or VS Code.

3. Ensure your MySQL server is running and the database is set up.

4. Run all cells in sequence.
---
🧠 Author
Ibrahim Ambale | ExploreAI Academy

Training future data analysts, one SQL query at a time.
---
📄 License
This project is licensed for educational use under the MIT License.
---
