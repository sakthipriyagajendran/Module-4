# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
# Define a list
list1 = [10, 20, 30]

# Use try-except block
try:
    # Attempt to access an out-of-range index
    print("Accessed element:", list1[5])
except IndexError:
    print("You're out of list range")

# Print final message
print("Program executed successfully")

## Output
<img width="382" height="249" alt="image" src="https://github.com/user-attachments/assets/14599481-4c21-4480-9d97-87cfa14b1be5" />

## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
