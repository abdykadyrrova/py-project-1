# Project Information:
This Python project reads the Spreadsheet file ("inventory.xlsx") and automates the following tasks:

1: Calculate how many Products we have per Supplier
Result should look like this: {'AAA Company': 43, 'BBB Company': 17, 'CCC Company': 14 }

2: List Products with Inventory less than 10

3: List each company with respective total Inventory value

4: Calculate Inventory value for each Product

# Instructions: 
- Install "openpyxl" package for it to be able to read spreadsheet file: pip install openpyxl
Documentation of the module: https://openpyxl.readthedocs.io/en/stable/api/openpyxl.worksheet.worksheet.html#module-openpyxl.worksheet.worksheet

- Copy the spreadsheet file into your repo and ingest it to python: 
inv_file = openpyxl.load_workbook("inventory.xlsx")
product_list = inv_file["Sheet1"]

Task 1: 
- In order to calculate how many Products we have per Supplier, we have to utilize for loop to read/count EACH row. 
- 