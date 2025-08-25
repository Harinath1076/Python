# Python
Python _Real_Scenario based Problems
#I have taken all the values using user input

#1.	Simulate Data:
customer_name=input("Enter customer name")
customer_age=int(input("Enter customer age"))

#enter a credit score between 0 to 900 
customer_credit_score = float(input("Enter credit score"))

#Enter number of transactions that shold be greater than zero
number_of_transactions = int(input("Enter Number of Transactions"))

initial_spending = float(input("Enter initial spending"))

print(customer_name)
print(customer_age)
print(customer_credit_score)
print(initial_spending)

print(number_of_transactions)

#2.	Use of Operators:

if number_of_transactions > 0:
  average_spending = (initial_spending/number_of_transactions)
else:
    print("Number of transactions must be greater than 0!")

print("average_spending per transaction is", average_spending)

#3.	Conditional Logic:
if customer_credit_score >= 800:
  print("Credit score is Excellent")
elif customer_credit_score >= 700:
  print("Credit score is Good")
else:
  print("Needs Improvement")

#4.	Looping Through Data:
total_spending = initial_spending
for i in range(1,number_of_transactions+1):
  transaction_amount = int(input("Enter transaction amount"))
  total_spending += transaction_amount
print("total_spending is", total_spending)

#5. Final output
print("average_spending per transaction is", average_spending)
print("total_spending is", total_spending)

