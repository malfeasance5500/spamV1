This document specifies extra module(s) required to run this program 

openpyxl module
- this program uses excel files to read data like the menu and the usernames and passwords
- openpyxl is a module that allows the program to open the excel file, read the excel file and edit the file as well
- openpyxl allows for shifting between sheets in a excel sheet
- openpyxl provides convenient functions , such as max_row, to get the max number of rows in the excel sheet, allowing the program to effectively loop through the excel file to get the information from the file

hashlib module
- hashlib is a module that allows the program to hash string inputs
- hashlib is used in the program to hash passwords when users create accounts for security purposes
- hashlib allows hashing, enabling the program to check with the hashed passwords in the excel files
