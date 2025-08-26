# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```
import re
s=input()
match=re.findall(r'^ab*$',s)
if match:
    print("Found a match!")
else:
    print("Not matched!")

```
### OUTPUT
<img width="951" height="317" alt="Screenshot 2025-08-26 200650" src="https://github.com/user-attachments/assets/5cad8979-78a0-44eb-8f7a-7c44fbc637aa" />

### RESULT
Thus the Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions is executed successfully.
