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

input_dict = {2: 56, 1: 2, 5: 12, 4: 24, 6: 18, 3: 323}
sorted_items = sorted(input_dict.items())
print("Keys and Values sorted in alphabetical order by the key")
for key, value in sorted_items:
    print(f"({key}, {value})", end=' ')
```
## Sample Output
<img width="961" height="218" alt="483846891-98d4921b-0283-4b50-969e-cdc004c60b42" src="https://github.com/user-attachments/assets/9818005f-1186-4434-80ac-1e451d503274" />


<img width="962" height="219" alt="483846902-4ed0bd37-9e56-45dd-a844-cf29d1e8813e" src="https://github.com/user-attachments/assets/bc0bfc32-e9ca-44ab-982b-475dc44c37fe" />

## Result
Thus the program executed successfully.
