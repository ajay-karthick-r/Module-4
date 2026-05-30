## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1 = {'a': 1, 'b': 2}
dict2 = {'c': 3, 'd': 4}

def merge():
    merged_dict = {**dict1, **dict2}
    return merged_dict

print(merge())
```
## Output
<img width="1396" height="263" alt="{5F467C61-C0A9-458E-9629-114DE32A585A}" src="https://github.com/user-attachments/assets/38c48388-c2b5-4ffd-99f1-8c85c51b8515" />

## Result
Thus ,the program has been excecuted successfully


