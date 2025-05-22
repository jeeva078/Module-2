# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - ADDING THREE NUMBERS

---

### AIM  
To write a Python program to check the Adding three numbers using a lambda function.

---

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1`,`num2`,`num3`) from the user.  
3. Define a lambda function `add` that takes three arguments `x`,`y`and`z`.  
4. The lambda function adding the numbers and prints:
   - lambda x,y,z:(x + 10) + (y + 2) * z
5. Call the lambda function by passing `num1`,`num2`and `num3` as arguments.  
6. Terminate the program.

---

### PROGRAM

```
x=int(input())
y=int(input())
z=int(input())
expr=lambda x,y,z:(x + 10) + (y + 2) * z
print(expr(x,y,z))
```

### OUTPUT
![image](https://github.com/user-attachments/assets/cf554520-a361-4a32-b98a-e5ad3b69b81c)

### RESULT
Thus,a Python program to check the Adding three numbers using a lambda function are verified  .
