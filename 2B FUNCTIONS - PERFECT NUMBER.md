# Exp.No:2b  
## FUNCTIONS - EVEN NUMBER

### AIM  
To write a Python program to check if a number is a Even number using the concept of functions.

---

### ALGORITHM

1. Begin the program.  
2. Read the number `x` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `even(n)` with the following steps:   
    - If a number `x` divides `2` perfectly (i.e., `x % 2 == 0`), add `x` to `factor_sum`.  
    - If is equal to `x`, then print the number is a Even number. Otherwise, print it's not a Even number.  
5. Terminate the program.

---

### PROGRAM
```
def func(x):
    if x % 2 == 0:
        print(f"{x} is Even number")
    else:
        print(f"{x} is Odd number")
x = 148
func(x)
```
### OUTPUT

![Screenshot 2025-04-28 133231](https://github.com/user-attachments/assets/f9361a18-7f1e-43d5-a6b0-62fb01245107)

### RESULT
Thus , a Python program to check if a number is a Even number using the concept of functions are verified.
