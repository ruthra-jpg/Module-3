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
~~~
import re
words = ["apple", "banana", "grape", "kiwi", "orange", "mango"]
filtered_words = [word for word in words if not re.search('e', word)]
print("Original list:", words)
print("Filtered list (without 'e'):", filtered_words)

~~~
## Output
<img width="1551" height="227" alt="image" src="https://github.com/user-attachments/assets/d233d00a-e254-452a-bd66-00fa915c4d6a" />

## Result
The code is executed successfully.
