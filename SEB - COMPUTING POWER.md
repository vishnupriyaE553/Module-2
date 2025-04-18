# Exp.No:10  
## SEB - COMPUTING POWER

---

### AIM  
To write a Python program to compute the power of a given number using an appropriate built-in function.

---

### ALGORITHM

1. Begin the program.  
2. Input the base number (`base`) from the user.  
3. Input the exponent number (`exp`) from the user.  
4. Use the built-in `pow()` function to compute the base raised to the power of the exponent.  
5. Print the result using the `print()` function, displaying the power in a formatted output.  
6. Terminate the program.

---

### PROGRAM

```python
base = int(input("Enter the base number: "))
exp = int(input("Enter the exponent: "))
res = pow(base, exp)
print(f"Power of the given number is: {res}")
