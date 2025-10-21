## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

Add code here
```
dict1={"string":3,"box":4,"fun":27}
dict2={"danger":4,"sun":8}
def merge(dict1,dict2):
    dict1.update(dict2)
    print(dict1)
merge(dict1,dict2)
```

## Output
<img width="1920" height="1080" alt="Screenshot (134)" src="https://github.com/user-attachments/assets/6fd445d2-80a7-4e1b-b28c-a6503a6ca4b6" />

## Result
