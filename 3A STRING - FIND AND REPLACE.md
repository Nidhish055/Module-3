# Exp.No:3a
## STRING - FIND AND REMOVE

---

### AIM  

To write a Python function that accepts a string and removes all the consonants from the string.

---

### ALGORITHM

1. Begin the program.
2. Input the original string str1 and the word to be replaced replace_str.
3. Ask the user to input the new replacement word str2.
4. Use the replace() method in Python to replace all occurrences of replace_str in str1 with str2.
5. Store the modified string in str3.
6. Display the original string (str1) and the modified string (str3).
7. Terminate the program.


---

### PROGRAM

```python
# Name : Nidhish B
# Reg no: 212223050032

def remove(n):
    vow=["a","e","o","u","i","I"]
    Str=""
    for i in n:
        if i in vow:
            Str=Str+i
    print(Str)
    
```

### OUTPUT

![image](https://github.com/user-attachments/assets/5e70930c-60b3-4179-afb5-0221130221b3)

### RESULT

Thus the program removes all consonants from the given string and prints only the vowels.
