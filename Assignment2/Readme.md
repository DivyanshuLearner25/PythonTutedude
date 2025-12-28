This is my Readme.md file to explain the all steps for Python Assignment2.
# Task1 
Checking a number given by user is even or odd.

  1. First I printed a message to user about the program using print() function .....

         print("This is a program to check whether the entered number by you is even or odd.")
  2. Used input() function (and int() for typocasting) to get user input

          user_input=int(input("Enter an integer number: "))
  3. Then checking condition using if statement:

             if user_input % 2 == 0:
  4. printed message using print()

           print(f"{user_input} is an even number.")
  6. print else condition with else statement.I have used in it fstring concept also.

          else:
              print(f"{user_input} is an odd number.")
# Task2
Using loop get the sum of numbers from 1 to 50 over every iteration.
















# Code 1
    #This is my first task of Assignment 2.
    # Code
    print("This is a program to check whether the entered number by you is even or odd.")
    # Taking Input from user (an integer)
    user_input=int(input("Enter an integer number: "))
    #Checking condition
    if user_input % 2 == 0:
        print(f"{user_input} is an even number.")
    else:
        print(f"{user_input} is an odd number.")
# Output 1
    This is a program to check whether the entered number by you is even or odd.
    Enter an integer number: 13
    13 is an odd number.
    
    Process finished with exit code 0
  2nd time when I run it 
  
        
    This is a program to check whether the entered number by you is even or odd.
    Enter an integer number: 106
    106 is an even number.
    
    Process finished with exit code 0
