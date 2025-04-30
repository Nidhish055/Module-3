# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers up to **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `n - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.

---

### PROGRAM

```python
#Name:Nidhish B
#Reg No: 212223050032
def createlist(n):
    s=[]
    for i in range(1,n):
        if i%2==0:
            s.append(i)
    print(s)
```

### OUTPUT

![image](https://github.com/user-attachments/assets/58d494e4-c098-465b-972c-8136ed46fd95)


### RESULT

The program generates and displays all even numbers up to the given number N.

