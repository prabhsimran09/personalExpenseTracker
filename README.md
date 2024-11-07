# personalExpenseTracker
Personal Expense Tracker in Python without OOPS

Code description :

I have created 7 methods namely –

1.	print_Menu() -> Main entry point of the project which provides the user with various options via which user can navigate to other interfaces of this project
	a.	1 -> add expense
	b.	2 -> view expense
	c.	3 -> track budget
	d.	4 -> save expense
	e.	5 -> exit

2.	add_expense() -> this method lets the user input expense details like category, amount, date and description. The expense is saved in a list but not in the csv file yet.
   
3.	view_expense() -> Loads all expenses added by user in this given session. These expenses are not saved to the csv, just those expenses are displayed which are present in the List
   
4.	track_budget() -> This method lets the user enter a budget amount for the month and calculates if total expenses that were entered in session and those from the csv file exceed the budget or not. (Only expenses for the particular month are taken into consideration)
   
5.	save_expense() -> Saves expenses entered in current session to the csv file
   
6.	load_expense() -> this method is called in the beginning of print_menu() method to load all records saved in csv file to the computer’s memory. These records are then used in track_budget() method
    
7.	total_expenses()->this method is called in the track_budget() method to calculates sum of expenses till date
