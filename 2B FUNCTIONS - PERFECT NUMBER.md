# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

### ALGORITHM

1. Begin the program.  
2. Read an integer input from the user and store it in n.
3. Initialize sum1 to 0 to store the sum of factors of n.
4. Use a for loop to iterate from 1 to n-1.
       If i is a factor of n (i.e., n % i == 0), add i to sum1.
5. After the loop, check if sum1 equals n.
       If true, print "The number is a Perfect number!".
       Otherwise, print "The number is not a Perfect number!".
6. Terminate the program.

### PROGRAM
```
#Reg.No:212223060305
#Name:Vishnu Priya E

n=int(input())
sum1=0
for i in range(1, n):
    if(n % i == 0):
        sum1 = sum1 + i
if(sum1 == n):
    print("The number is a Perfect number!")
else:
    print("The number is not a Perfect number!")
```
### OUTPUT
<img width="913" height="221" alt="image" src="https://github.com/user-attachments/assets/79cb33fb-7a9c-46d8-94d7-c5c8b62a0181" />

### RESULT
Thus a Python program to check if a number is a Perfect number using the concept of functions was executed and implemented successfully.
