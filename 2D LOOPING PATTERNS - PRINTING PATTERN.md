# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

### AIM  
To write a Python program to print a triangular star pattern using loops.

### ALGORITHM

1. Begin the program.  
2. Read an integer input from the user and store it in r.
3. Initialize m = r + 1.
4. Use a for loop to iterate i from 0 to m-1.
     Print "  " * (r-1) to create left spacing.
     Print " " * i + "* " * (m-i) to display the stars with proper spacing.
5. Terminate the program.

### PROGRAM
```
#Reg.No:212223060305
#Name:Vishnu Priya E

r=int(input())
m=r+1
for i in range(0,m):
    print("  "*(r-1),end="")
    print(" "*i+"* "*(m-i))
```

### OUTPUT
<img width="899" height="653" alt="image" src="https://github.com/user-attachments/assets/c91028c9-2aee-4937-aa1e-24a6eed1dedb" />

### RESULT
Thus a Python program to print a triangular star pattern using loops was executed and implemented successfully.
