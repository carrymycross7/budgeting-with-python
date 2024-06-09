# This will be a python based budgeting app

# To install requirements run: pip install -r requirements.txt

# Will have categories
## eg: Food, Gas, Extra, Normal Bills (Mortgage,Loans,Orkin,Electric,Water,Internet)
# Allow option to enter in to deduct from the amount
##   eg: Food budget = 200 -> user input 50 -> 200 - 50 -> Food Budget = 150
# Allow user to set schedule on when the bills reset
## eg: Extra may reset bi-weekly, Water is monthly
# Will send out email notification to users when a budget is overbalanced
## eg Food Budget 50 -> user input 75 -> 50 - 75 -> Food Budget = -25 -> email user on file showing the overdraft of the budget

# Phase 1
## All Catgeories will be saved on an .env file
## All schedules will be saved on that env file
## Will be command line only program

# Phase 2
## Categories will be saved on a postgres database
## Schedules will be on a separate postgres database, with foreign keys to tie to the categories
## User implementation
### Username and password
## Users will be stored on a postgres database