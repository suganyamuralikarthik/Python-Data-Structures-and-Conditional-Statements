# 🐍 Python Data Structures and Conditional Statements

## 📌 Overview

This project covers basic Python concepts including **Lists, Dictionaries, Sets, and Conditional Statements**.

## 📋 List

```python
age_list = [24, 25, 27, 28, 29]
name_list = ["Suganya", "Divya", "Ramya", "Geetha", "Shruthi"]

name_list.append("Yazhini")
age_list.insert(2, 26)
name_list.remove("Yazhini")
age_list.pop()
age_list.extend([31, 30, 32])
age_list.sort(reverse=True)

print("Maximum:", max(age_list))
print("Minimum:", min(age_list))
print("Sum:", sum(age_list))

print(name_list[0])
print(name_list[-1])
print(name_list[2:5])
print(name_list[::-1])
