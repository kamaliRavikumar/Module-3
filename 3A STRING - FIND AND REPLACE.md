# Exp.No:3a
## STRING - FIND AND REPLACE

---

### AIM  
To write a python function "remove" that accepts a string and removes all the vowels from the string.
### ALGORITHM

1. Start the program.
2. Define a function remove(s) that will take a string as input.
3. Store all vowels (both lowercase and uppercase) in a variable vowels = "aeiouAEIOU".
4. Scan each character i in the string s.
5. Check if the character i is not in the set of vowels.
6. Form a new string result by joining all non-vowel characters together.
7. Display the final string without vowels and end the program.
---

### PROGRAM

```
def remove(s):
    vowels = "aeiouAEIOU"
    result = "".join(i for i in s if i not in vowels)
    print(result)

s=input()

```

### OUTPUT
<img width="950" height="231" alt="Screenshot 2025-08-26 200314" src="https://github.com/user-attachments/assets/956da3ad-17b6-4a61-8993-bb1bae1b313e" />

### RESULT
Thus the python function "remove" that accepts a string and removes all the vowels from the string is executed successfully.
