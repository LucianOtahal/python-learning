# 💰 Minimum and Maximum - Product Price Analyzer (MSRP)
This Python script connects to a PostgreSQL database and identifies the cheapest and most expensive product based on the MSRP (Manufacturer’s Suggested Retail Price).
# 🔧 What it does:
- Connects to a PostgreSQL database using psycopg2
- Queries all products and their MSRP values
- Iterates through the results to:
- Track the lowest price using math.inf
- Track the highest price starting from 0
- Displays the final min and max MSRP values
# 🧠 Key concepts:
- SQL query: SELECT productname, MSRP FROM products
- Looping through query results
- Conditional comparison to update min/max values
- Use of math.inf for safe initialization
# ▶️ How to run:
Make sure your database is running and credentials are correct, then execute:
python script.py


#📦 Requirements:
- Python 3
- psycopg2 library (pip install psycopg2)
- PostgreSQL database with a products table containing productname and MSRP columns



