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

# 🗃️ SQL Data Loader & Price Analyzer
This Python script connects to a PostgreSQL database and runs several SQL queries to explore product and order data. It also calculates the average purchase price of products.
🔧 What it does:
- Establishes a connection to a PostgreSQL database using psycopg2
- Uses a cursor object to:
- Send SQL queries to the database
- Retrieve and iterate over results row by row
- Executes and displays results for:
- All products from the Motorcycles product line
- Products with stock > 1000 and price < 20 PLN
- Orders made in 2003
- Orders from 2003 that were canceled
- Calculates the average buy price from the products table

# 🧠 Key concepts:
- The cursor is the interface between Python and the database — it sends queries and fetches results
- SQL filtering with WHERE clauses
- Iterating through query results using for row in cursor
- Using rowcount and basic math to compute averages safely
# ▶️ How to run:
Use Jupyter Notebook or any Python environment:

# 📦 Requirements:
- Python 3
- psycopg2 (pip install psycopg2)
- PostgreSQL database with relevant tables (products, orders)


