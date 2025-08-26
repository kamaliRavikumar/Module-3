# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 9 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_9` with values starting from `9` up to `N - 1`, stepping by `9`.  
4. Return the tuple `multiples_of_9`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
N = int(input())
multiples= tuple(x for x in range(9, N, 9))
print(multiples)
print("Length of the tuple is", len(multiples))
```

### OUTPUT
<img width="1013" height="271" alt="Screenshot 2025-08-26 201711" src="https://github.com/user-attachments/assets/12026332-0adf-4974-a42d-64aefb9c2d6b" />

### RESULT
Thus the Python program to create a tuple containing all multiples of 5 up to a given number **N** is executed successfully.
