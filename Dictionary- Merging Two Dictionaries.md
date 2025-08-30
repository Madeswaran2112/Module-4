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
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
```
## Output
<img width="966" height="290" alt="483846868-f23ce4cf-ecdb-48e1-88f5-d6ba76556030" src="https://github.com/user-attachments/assets/2093e8d0-3f55-4172-bcb7-1b16420f73df" />

## Result
Thus the program executed successfully.
