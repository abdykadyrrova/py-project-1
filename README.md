# Project Information:
This Python project reads the Spreadsheet file ("inventory.xlsx") and automates the following tasks:

1: Calculate how many Products we have per Supplier. 
Result should look like this: {'AAA Company': 43, 'BBB Company': 17, 'CCC Company': 14 }

2: List each company with respective total Inventory value

3: List Products with Inventory less than 10

4: Add a fifth column to the spreadsheetnfor total inventory price

# Instructions: 
- Install "openpyxl" package for it to be able to read spreadsheet file: pip install openpyxl 
- Documentation of the module: https://openpyxl.readthedocs.io/en/stable/api/openpyxl.worksheet.worksheet.html#module-openpyxl.worksheet.worksheet
- Copy the spreadsheet file into your repo and ingest it to python
- In order to calculate how many Products we have per Supplier, we have to utilize for loop to read/count EACH row. 
- use range() since it creates a sequence of numbers, starting from 0 by default. Start from row 2 and add +1 to the max_row.
- Identify where every cell is located, Supplier name for example is on: cell(product_row, 4)
- Follow the code for the logic

