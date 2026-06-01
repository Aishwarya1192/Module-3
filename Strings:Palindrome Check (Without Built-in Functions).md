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

Add code here
s = "google"
reverse = ""

for ch in s:
    reverse = ch + reverse

if s == reverse:
    print(f'"{s}" is a Palindrome')
else:
    print(f'"{s}" is Not a Palindrome')


## Output
"google" is Not a Palindrome


## Result
Hence the output is verified
