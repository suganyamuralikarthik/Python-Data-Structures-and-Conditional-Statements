# Python-Data-Structures-Lists-Dictionaries-Sets

This repository contains Python programs demonstrating **List, Dictionary, Set, and Conditional Statement operations**. Includes assignment solutions, examples, and explanations for learning basic Python data structures.

---

## Overview

This assignment covers essential Python concepts:

• Creating and modifying lists  
• List indexing and slicing  
• List methods and built-in functions  
• Creating and modifying dictionaries  
• Dictionary methods such as `keys()`, `values()`, and `items()`  
• Creating sets and removing duplicate values  
• Set union and intersection  
• Conditional statements using `if`, `elif`, and `else`  
• Taking user input and performing decision-making  

---

## List Concepts Covered

• List Creation  
• `append()`  
• `insert()`  
• `remove()`  
• `pop()`  
• `extend()`  
• Sorting in descending order  
• `max()`, `min()`, and `sum()`  
• Indexing  
• Slicing  
• Reversing a list  

### Example

```python
age_list = [24, 25, 27, 28, 29]

name_list = ["Rakshan", "Raghav", "Pranish", "Nikhilan", "Vihaan"]

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
Maximum: 32
Minimum: 24
Sum: 213

Rakshan
Vihaan
['Pranish', 'Nikhilan', 'Vihaan']
['Vihaan', 'Nikhilan', 'Pranish', 'Raghav', 'Rakshan']
Dictionary Concepts Covered

• Dictionary Creation
• Accessing dictionary values
• Adding new key-value pairs
• Updating existing values
• keys()
• values()
• items()

Example
student_marks = {
    "Rakshan": 85,
    "Raghav": 90,
    "Pranish": 75,
    "Nikhilan": 88,
    "Vihaan": 92
}

print(student_marks["Rakshan"])

student_marks["Janani"] = 80
student_marks["Pranish"] = 82

print(student_marks.keys())
print(student_marks.values())
print(student_marks.items())
Output
85

dict_keys(['Rakshan', 'Raghav', 'Pranish', 'Nikhilan', 'Vihaan', 'Janani'])

dict_values([85, 90, 82, 88, 92, 80])
🔤 Set Concepts Covered

• Set Creation
• Removing duplicate values
• Understanding unordered collections
• Set Union
• Set Intersection
• Understanding set indexing

Example
my_set = {'a', 'e', 'i', 'o', 'u', 'a', 'a', 'i'}

print(my_set)
Output
{'a', 'e', 'i', 'o', 'u'}
Explanation

Sets automatically remove duplicate values.

set1 = {1, 3, 5, 7, 9}
set2 = {2, 3, 5, 8, 10}

print("Union:", set1.union(set2))
print("Intersection:", set1.intersection(set2))
Output
Union: {1, 2, 3, 5, 7, 8, 9, 10}

Intersection: {3, 5}

Sets do not support indexing because they are unordered collections.

🔀 Conditional Statements

Conditional statements are used to make decisions based on a given condition.

Performance Category Program
score = int(input("Enter your score (0 to 10): "))

if score > 7:
    print("Above Average: Excellent performance!")

elif score >= 4:
    print("Average: Good effort! Keep practicing.")

else:
    print("Below Average: Need to improve your performance.")
Sample Output
Enter your score (0 to 10): 7
Average: Good effort! Keep practicing.
## 🔑 Key Insights

• Lists are **ordered and mutable**, allowing elements to be added, removed, and modified.  
• Dictionary data is stored as **key-value pairs** for easy access and updates.  
• Sets store **unique values** and automatically remove duplicates.  
• List slicing helps access a specific range of elements.  
• `append()` adds one element, while `extend()` adds multiple elements.  
• `union()` combines unique elements from two sets, while `intersection()` finds common elements.  
• Conditional statements (`if`, `elif`, `else`) help make decisions based on conditions.  
• User input can be combined with conditional statements to create interactive programs.
📂 Project File

Python Data Structures - Lists, Dictionaries, Sets & Conditional Statements.ipynb

👩‍💻 Author

D. Suganya

Module 4 – Python Basics

Data Structures: Lists, Dictionaries, Sets & Conditional Statements


