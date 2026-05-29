## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```python
dict1 = {"a": 1, "b": 2}
dict2 = {"c": 3, "d": 4}

dict1.update(dict2)

print("Merged Dictionary:", dict1)
```

## Output
<img width="465" height="53" alt="Screenshot 2026-05-29 202039" src="https://github.com/user-attachments/assets/66961403-43fa-4816-841a-1f7cecf246b5" />

## Result
The code was executed successfully by using Python
