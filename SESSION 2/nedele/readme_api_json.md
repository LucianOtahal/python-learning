

# 📊 NBP Exchange Rates Fetcher
This Python script uses the  library to retrieve current exchange rates from the public API of the National Bank of Poland (NBP).
🔧 What it does:
• 	Connects to the API: 
• 	Parses the JSON response
• 	Iterates through the list of currencies
• 	Displays each currency’s code, name, and exchange rate () in the format:

USD (dolar amerykański): 3.635 PLN
EUR (euro): 4.2593 PLN
...
# 🧠 Key concepts:
- The API returns a list of tables; each contains a list of currencies as dictionaries
- A for loop reads each currency entry and extracts code, currency, and mid
- Uses Python f-strings for clean, formatted output
# ▶️ How to run:
Make sure you have Python 3 installed, then run:
python script.py


# 📦 Requirements:
- requests (install via pip install requests)
