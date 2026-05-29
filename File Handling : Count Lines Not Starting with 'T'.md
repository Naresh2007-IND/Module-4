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
```python
count = 0

file = open("sample.txt", "r")

for line in file:

    # Check if line does not start with 'T'
    if line[0] != 'T':
        count += 1

file.close()

print("Number of lines not starting with 'T':", count)
```

## Output
<img width="378" height="44" alt="Screenshot 2026-05-29 203057" src="https://github.com/user-attachments/assets/7718372a-149c-4eca-bf1c-7bca5ef9274f" />

## Result
The code was successfully executed by using Python
