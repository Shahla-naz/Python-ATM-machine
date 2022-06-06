# Python-ATM-machine
bal = 1000
transaction = 'yes'
while transaction!='no':
    print("*****Welcome to ABC ATM System*****")
    print("1-->CHECK BALANCE")
    print("2-->DEPOSIT")
    print("3-->WITHDRAW")
    print("4-->EXIT")
    choice=int(input("Please enter your choice:"))
    if choice in (1,2,3,4):
        if choice==1:
            print("your current balance is:", bal)
        elif choice==2:
            print("Enter the amount to deposit:")
            deposit = int(input())
            bal = bal + deposit
            print("your current balance is:", bal)
        elif choice==3:
            print("Enter the withdraw amount:")
            withdraw = int(input())
            bal = bal - withdraw
            print("your current balance is:", bal )
        elif c
elif choice==3:
            print("Enter the withdraw amount:")
            withdraw = int(input())
            bal = bal - withdraw
            print("your current balance is:", bal )
        elif choice==4:
            print("Thank you!")
            break
        else:
            print("please enter correct choice")
    
    transaction = input("Would you like to continue:(yes/no):")  
else:
    print("Thank you!")
