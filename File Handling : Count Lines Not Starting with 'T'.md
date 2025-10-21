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
Add code here
```
with open ("start.txt","r") as f:
    count=0
    for i in f:
        if not i.startswith("T"):
            count+=1

     print("Number of lines that do not start with 'T':",count)
   f.close()

```
## Output
<img width="1920" height="1080" alt="Screenshot (137)" src="https://github.com/user-attachments/assets/ca05eaa5-e86c-4fbb-9ea6-dd780a6d972e" />

## Result
