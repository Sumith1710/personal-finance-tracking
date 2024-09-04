# personal-finance-tracking
This is a personal finance Tracking project using python
In this project we are going to import padas and matplotlib libraries
First we need create a class then we need create class methods representing the action to be made when its called
initialize_csv method will read or create a csv file wnen its not present  for storing the information (date,amount,category,decription). we can call this methon using "CSV.ainitialize_csv()"
add_entry method is used for storing the information (date,amount,category,decription) in finanace_data csv file
get_transactions method is used to retrive the trasaction between start_date and end_date from finanace_data csv file and calculate total income , total expenses and net saving 
add() function is used to call Initialize_csv method 
plot_transactions() function is used to represent matplotlib gragh From start_date to end_date
main() function contain the command call the all the class method 
data_entry.py is python for storing the information (date,amount,category,decription)  about trasaction for keeping the code simple from main.py file.
