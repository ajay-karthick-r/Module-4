# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
pi_value=math.pi
class cse:
    def mech(self,radius):
        print("Area of circle:",round(pi_value*radius**2,2))
circle=cse()      
radius=float(input())
circle.mech(radius)
```
## Output
<img width="1277" height="270" alt="{9639CCCD-B02E-4453-97FF-AE1C8A984F84}" src="https://github.com/user-attachments/assets/3d89f5c3-e295-4c7c-9522-4cd67decf781" />


## Result
Thus , the program has been excecuted successfully

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
```
list1 = [10, 20, 30, 40]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
```
## Output
<img width="1262" height="246" alt="{7F2524E7-F2C5-4755-BBA3-7E670553E842}" src="https://github.com/user-attachments/assets/c4ce4730-c07c-493f-8112-349a4ebc6f8d" />

## Result
Thus , the program has been excecuted successfully

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
file=open("story.txt","r") 
count=0 
for lines in file: 
   if lines [0] not in 'T': 
      count+=1 
print(count)
```
## Output
<img width="1101" height="708" alt="{2F1B3235-7CDF-4441-81C5-CEFAA8A12CD5}" src="https://github.com/user-attachments/assets/ecb82b97-e834-430b-902a-e4254b94d0cf" />


## Result
Thus , the program has been excecuted successfully

