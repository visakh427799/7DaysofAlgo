# Code
```python
'''
Documentation
Program to check whether the given number is prime or not

Name  : Thushar Thomas
Branch: AI & DS
'''

def is_prime(num):  #Declaring a function
    fact=1
    for i in range(2,num+1):
        if num%i==0:  #Checking for factors
            fact=fact+1
    if (fact==2):
        return True
    else:
        return False
        
n = int(input("Enter a number: "))  #Getting a number from user

is_prime(n)
```

# Explanation
The program above checks whether the number from the user is a prime number or not. 
<p>Prime number is a number that has only 2 factors. In this progam we check the number of factors for a number using for loop and if condition.</p>
If the number only has 2 factors, 'if else condition' returns 'True'. If not 'False'.

<p>Thank you</p>
