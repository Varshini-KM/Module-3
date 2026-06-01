# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
string = "google"
rev = string[::-1]

if string == rev:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")
```
## Output
<img width="610" height="695" alt="image" src="https://github.com/user-attachments/assets/2f4a3290-a918-4b8b-babc-574234eaa7ac" />


## Result
Thus, the program has been excecuted successfully.


