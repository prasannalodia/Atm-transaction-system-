import numpy as np


pin = 1234
balance = 10000

print("ATM Kiosk Started")


user_pin = int(input("Enter PIN: "))

if user_pin == pin:
    print("PIN Verified")
    
    
    amount = int(input("Enter amount to withdraw: "))
    
    if amount <= balance:
        balance = balance - amount
        print("Transaction Successful")
        print("Withdrawn Amount:", amount)
        print("Remaining Balance:", balance)
    else:
        print("Insufficient Balance")
        
else:
    print("Invalid PIN")1234

    
