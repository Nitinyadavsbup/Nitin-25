# Nitin-25
this is my first Git repository
'''Write a Python program to input a positive integer. Display correct message for 
correct and incorrect input. (Use Exception Handling) '''

while True:
    try:
        num1 = int(input('Enter First No.::'))
        print(num1)

    except Exception as e:
        print("Generic Handler : Err. Desc. ::", e)
