# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
# Start the program

# Define a dictionary
my_dict = {'b': 3, 'a': 1, 'd': 4, 'c': 2}

# Sort by keys
sorted_by_keys = dict(sorted(my_dict.items()))

# Sort by values
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

# Display results
print("Original Dictionary:", my_dict)
print("Dictionary sorted by keys:", sorted_by_keys)
print("Dictionary sorted by values:", sorted_by_values)


## Sample Output
<img width="657" height="221" alt="image" src="https://github.com/user-attachments/assets/81b79ca2-a975-4df6-a2d2-48aa93850486" />

## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
