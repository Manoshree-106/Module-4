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
    "The sun rises.",
    "today is bright.",
    "Time flies.",
    "life goes on."
]
count = 0
for line in lines:
    if not line.startswith('T'):
        count += 1

print("Number of lines not starting with 'T':", count)
```

## Output
<img width="1233" height="415" alt="image" src="https://github.com/user-attachments/assets/82dde76a-e6ae-49e7-a27a-a3b44da0804b" />

## Result
The code executed successfully.
