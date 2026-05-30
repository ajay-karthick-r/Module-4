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
```
d = {
    5: 50,
    2: 20,
    8: 80,
    1: 10
}

print("Original Dictionary:")
print(d)

sorted_keys = dict(sorted(d.items()))
print("\nDictionary sorted by keys:")
print(sorted_keys)

sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))
print("\nDictionary sorted by values:")
print(sorted_values)
```
## Sample Output
<img width="1224" height="511" alt="{19F5D681-49EA-4CE4-8CCF-AFCFE60EAFCA}" src="https://github.com/user-attachments/assets/27d620ed-9bb6-4493-a98f-825cad76c832" />


## Result
Thus , the program has been excecuted successfully



