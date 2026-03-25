# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
count = 0

try:
    with open("story.txt", "r") as file:
        for line in file:
            # Remove leading/trailing whitespace
            line = line.strip()
            
            # Check if line is not empty and does not start with 'T'
            if line and not line.startswith('T'):
                count += 1

    print("Number of lines not starting with 'T':", count)

except FileNotFoundError:
    print("The file 'story.txt' was not found.")

## Output
<img width="404" height="211" alt="image" src="https://github.com/user-attachments/assets/f4634840-4927-4b5c-9d22-2ae51284ee22" />

## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
