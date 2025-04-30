# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 9

---

### AIM  

To write a python program to create the tuple by the multiples of 9 up to N and the print length of the tuple.

---

### ALGORITHM

1. Begin the program.
2. Accept an integer N from the user.
3. Use a generator expression inside the tuple() function to create a tuple 'multiples_of_9' with values starting from 9 up to N (inclusive), stepping by 9.
4. Print the resulting tuple.
5. Use the len() function to find and print the length of the tuple.
6. Terminate the program.

---

### PROGRAM

```python

# Name : Nidhish B
# Reg No : 212223050032

n=int(input())
s=[]
for  i in range(1,n):
    if i%9==0:
        s.append(i)
print(tuple(s))
print(f"Length of the tuple is",len(s))

```

### OUTPUT

![image](https://github.com/user-attachments/assets/4fd3d36d-382b-4860-9388-dd63dcfd168e)

### RESULT

The program successfully creates a tuple containing the multiples of 9 up to the given number N and prints its length.
