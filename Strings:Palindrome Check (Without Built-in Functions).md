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
~~~
word = "google"
reversed_word = ""
for char in word:
    reversed_word = char + reversed_word
if word == reversed_word:
    print(word, "is a palindrome.")
else:
    print(word, "is not a palindrome.")
~~~

## Output
<img width="1340" height="331" alt="image" src="https://github.com/user-attachments/assets/c95c210e-aa9e-4b2b-bd7a-c9f936517639" />

## Result
The code is executed successfully.
