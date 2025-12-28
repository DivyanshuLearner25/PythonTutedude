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
  1. First i created a variable  sum_of_integers giving an integer value 0.
     my objective was to store sum of integers over every iteration

    sum_of_numbers=0
  2.. I run for loop from 1 to 5.

    for j in range(1,51,1): 
  3.. I wrote the statement inside the for loop
  given below to store and add the sum of each oteration.

    sum_of_numbers+=j
  4.. In last i printed the final output.
     First time inside tthe loop.To get outputs during every iteration. 
     Second time outside the loop to only get the final output from the
      varible created one line above for loop.
      
    print(f"The sum of numbers from 1 to {j} is {sum_of_numbers}.")

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

# Code 2 
     # To show the output of each iteration
    sum_of_numbers=0
    for j in range(1,51,1):
        sum_of_numbers+=j
        print(f"The sum of numbers from 1 to {j} is {sum_of_numbers}.")
    # Only Final Output
    sum_of_numbers=0
    for j in range(1,51,1):
        sum_of_numbers+=j
    print(f"The sum of numbers from 1 to {j} is {sum_of_numbers}.")
# Output 2
  FOR :
   To show the output of each iteration
      The sum of numbers from 1 to 1 is 1.
      The sum of numbers from 1 to 2 is 3.
      The sum of numbers from 1 to 3 is 6.
      The sum of numbers from 1 to 4 is 10.
      The sum of numbers from 1 to 5 is 15.
      The sum of numbers from 1 to 6 is 21.
      The sum of numbers from 1 to 7 is 28.
      The sum of numbers from 1 to 8 is 36.
      The sum of numbers from 1 to 9 is 45.
      The sum of numbers from 1 to 10 is 55.
      The sum of numbers from 1 to 11 is 66.
      The sum of numbers from 1 to 12 is 78.
      The sum of numbers from 1 to 13 is 91.
      The sum of numbers from 1 to 14 is 105.
      The sum of numbers from 1 to 15 is 120.
      The sum of numbers from 1 to 16 is 136.
      The sum of numbers from 1 to 17 is 153.
      The sum of numbers from 1 to 18 is 171.
      The sum of numbers from 1 to 19 is 190.
      The sum of numbers from 1 to 20 is 210.
      The sum of numbers from 1 to 21 is 231.
      The sum of numbers from 1 to 22 is 253.
      The sum of numbers from 1 to 23 is 276.
      The sum of numbers from 1 to 24 is 300.
      The sum of numbers from 1 to 25 is 325.
      The sum of numbers from 1 to 26 is 351.
      The sum of numbers from 1 to 27 is 378.
      The sum of numbers from 1 to 28 is 406.
      The sum of numbers from 1 to 29 is 435.
      The sum of numbers from 1 to 30 is 465.
      The sum of numbers from 1 to 31 is 496.
      The sum of numbers from 1 to 32 is 528.
      The sum of numbers from 1 to 33 is 561.
      The sum of numbers from 1 to 34 is 595.
      The sum of numbers from 1 to 35 is 630.
      The sum of numbers from 1 to 36 is 666.
      The sum of numbers from 1 to 37 is 703.
      The sum of numbers from 1 to 38 is 741.
      The sum of numbers from 1 to 39 is 780.
      The sum of numbers from 1 to 40 is 820.
      The sum of numbers from 1 to 41 is 861.
      The sum of numbers from 1 to 42 is 903.
      The sum of numbers from 1 to 43 is 946.
      The sum of numbers from 1 to 44 is 990.
      The sum of numbers from 1 to 45 is 1035.
      The sum of numbers from 1 to 46 is 1081.
      The sum of numbers from 1 to 47 is 1128.
      The sum of numbers from 1 to 48 is 1176.
      The sum of numbers from 1 to 49 is 1225.
          The sum of numbers from 1 to 50 is 1275.
          
          Process finished with exit code 0
 FOR ONLY FNAL OUTPUT 
              
    The sum of numbers from 1 to 50 is 1275.
    Process finished with exit code 0
