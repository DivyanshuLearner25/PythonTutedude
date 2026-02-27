Readme.md file
# Assignment 3
# Task1: 
Calculate Factorial Using a Function 
#  
1> created a user_num variable to store an integer number entered by user.
        
        user_num=int(input('Enter a number :'))
2> defined function using def keyword with function name fact and parameter num
 
     def fact(num):
3> checks conditions using if-else python conditional statement 
used fact() inside function[recursive function] to iterate it till a certain condition.

    if num==0:
        return 1
    else:
        return num*fact(num-1)

4> stored the returned value in result variable and in the same line i called the function fact() and as argument i gave the user input user_num
in last i printed result.

    result=fact(user_num)
    print(result)
#   

# Code
    user_num=int(input('Enter a number :'))
    def fact(num):
        if num==0:
            return 1
        else:
            return num*fact(num-1)
    result=fact(user_num)
    print(result)
#   
# Output 
[ I run it 2 times.]
 RUN 1

     C:\Users\PS\AppData\Local\Programs\Python\Python314\python.exe "E:\Learning DM\Python World\Tutedude\Python_tutedude_practical.py" 
    Enter a number :5
    120

    Process finished with exit code 0

 RUN 2

     C:\Users\PS\AppData\Local\Programs\Python\Python314\python.exe "E:\Learning DM\Python World\Tutedude\Python_tutedude_practical.py" 
    Enter a number :8
    40320

    Process finished with exit code 0
#   
# Task 2
  Using the Math Module calculate the:
  o   Square root of the number
  o   Natural logarithm (log base e) of the number
  o   Sine of the number (in radians)
#    
  step1:

