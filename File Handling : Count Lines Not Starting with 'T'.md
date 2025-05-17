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
```
lines = [
    "The sun rises in the east.",
    "Tomorrow will be a great day.",
    "Birds are singing.",
    "Trees are green.",
    "Today is sunny.",
    "Grass is wet with dew."
]

count = 0
for line in lines:
    if not line.startswith('T'):
        count += 1

print(count)
```

## Output
![image](https://github.com/user-attachments/assets/4ee81a30-a5f6-4ec4-8aac-0ad4004fe340)

## Result
The Python program to count lines not starting with 'T' in story.txt has been executed successfully, and the output has been verified.
