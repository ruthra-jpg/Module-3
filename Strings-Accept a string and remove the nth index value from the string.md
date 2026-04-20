# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
~~~
user_string = input("Enter a string: ")
index = int(input("Enter the index of the character to remove: "))
if 0 <= index < len(user_string):
    modified_string = user_string[:index] + user_string[index+1:]
    print("String after removing character:", modified_string)
else:
    print("Invalid index! Please enter a valid index.")
~~~


## Output
<img width="1282" height="303" alt="image" src="https://github.com/user-attachments/assets/670d0685-294c-4e18-b974-9e47fc833325" />

## Result
The code is executed successfully.
