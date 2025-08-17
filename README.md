
# Q1. 
## If-Else and Elif Statements 

Write a Python function called check_grade that takes a score as input and prints "Pass" if the score is 50 or higher, and "Fail" otherwise. Extend the function to print "Excellent" if the score is 90 or above.   

```Python
# Question 1 

score_input = float(input("Enter the score: \n"))
check_grade = (score_input)
if check_grade >= 90:
    print ("Excellent")
elif check_grade >= 50:
    print ("Pass")
else:
    print ("Fail")

