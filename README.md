# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```python

Program to find the gcd of two number using function.
Developed by: VIKASH S
RegisterNumber: 22008879 
def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
       smaller=n2
    else:
        smaller=n1
    for i in range(1,smaller+1):
        if(n1%i==0 and n2%i==0):
            hcf=i
            
    print("GCD of two numbers is:",hcf)
   
```

## Output:
![gcd ](https://user-images.githubusercontent.com/119433834/210180086-4983fcba-5953-423f-997d-eb5db186fa0b.png)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
