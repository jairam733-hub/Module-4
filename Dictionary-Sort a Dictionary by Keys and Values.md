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
Add Code here
```

a= {'banana': 3, 'apple': 5, 'cherry': 2, 'date': 4}
sorted_by_keys = dict(sorted(a.items()))
sorted_by_values = dict(sorted(a.items(), key=lambda item: item[1]))


print("Original Dictionary:", a)
print("Dictionary Sorted by Keys:", sorted_by_keys)
print("Dictionary Sorted by Values:", sorted_by_values)
```

## Sample Output
<img width="1920" height="1080" alt="Screenshot (135)" src="https://github.com/user-attachments/assets/e2839153-c1df-47fa-bc24-c3599f0f030e" />

## Result

