# Exp.No:3e
## SEB - JOINING STRINGS WITH A SYMBOL

---

### AIM  
To write a python function to accept the string and the symbol, return the string joined by the symbol.

---

### ALGORITHM

1. Begin the program.
2. Define a function that accepts two parameters: a list of strings and a symbol.
3. Use the join() method to concatenate the list elements, inserting the symbol between each element.
4. Return the resulting string.
5. Terminate the program.


---

### PROGRAM

```python

# Name : Nidhish B
# Reg No : 212223050032

def joinstring(a,b):
    d=[]
    Str=""
    for i in a:
        d.append(i)
        d.append(b)
        c=len(d)
    d.pop(c-1)
    for i in d:
        Str=Str+i
    print(Str)


```

### OUTPUT

![image](https://github.com/user-attachments/assets/8fd46d28-3f15-4f26-a0b7-76b761e36e0d)


### RESULT

Thus the python program to accept the string and the symbol, return the string joined by the symbol is successfully executed.
