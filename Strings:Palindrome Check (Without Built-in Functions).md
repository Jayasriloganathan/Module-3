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

````
s = "google"
reversed_s = s[::-1]

if s == reversed_s:
    print(s, "is a palindrome.")
else:
    print(s, "is not a palindrome.")
````

## Output

<img width="525" height="156" alt="image" src="https://github.com/user-attachments/assets/c20c43e9-dfab-4d88-a926-6ea37ff64e60" />

## Result

Thus the program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions has been executed successfully.
