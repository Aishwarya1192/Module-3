# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
Add code here
import re

words = ["apple", "banana", "grape", "kiwi", "mango", "pear", "plum"]

filtered = [w for w in words if not re.search("e", w)]

print("Original list:", words)
print("Filtered list (no 'e'):", filtered)

## Output
Original list: ['apple', 'banana', 'grape', 'kiwi', 'mango', 'pear', 'plum']
Filtered list (no 'e'): ['banana', 'kiwi', 'mango', 'plum']


## Result
Hence the output is verified
