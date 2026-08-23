# Python-Data-Structures-Lists-Dictionaries-Sets

This repository contains Python programs demonstrating **List, Dictionary, Set, and Conditional Statement operations**. Includes assignment solutions, examples, and explanations for learning basic Python data structures.

---

## Overview

This assignment covers essential operations in Python data structures:

• Creating and modifying lists  
• Accessing list elements using indexing and slicing  
• Applying common list methods  
• Creating and modifying dictionaries  
• Using dictionary methods  
• Creating sets and removing duplicate values  
• Performing set union and intersection  
• Applying conditional statements using `if`, `elif`, and `else`

---

## List Concepts Covered

• List Creation  
• `append()`  
• `insert()`  
• `remove()`  
• `pop()`  
• `extend()`  
• Sorting in descending order  
• `max()`  
• `min()`  
• `sum()`  
• Positive & Negative Indexing  
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
Output
Maximum: 32
Minimum: 24
Sum: 213
List Accessing

Lists can be accessed using indexing and slicing.

Example
print(name_list[0])
print(name_list[-1])
print(name_list[2:5])
print(name_list[::-1])
Output
Rakshan
Vihaan
['Pranish', 'Nikhilan', 'Vihaan']
['Vihaan', 'Nikhilan', 'Pranish', 'Raghav', 'Rakshan']
Dictionary Concepts Covered

• Dictionary Creation
• Accessing values
• Adding new key-value pairs
• Updating values
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
• Union
• Intersection
• Set indexing

Example
my_set = {'a', 'e', 'i', 'o', 'u', 'a', 'a', 'i'}

print(my_set)
Output
{'a', 'e', 'i', 'o', 'u'}

Duplicate values are automatically removed from a set.

Union and Intersection
set1 = {1, 3, 5, 7, 9}
set2 = {2, 3, 5, 8, 10}

print("Union:", set1.union(set2))
print("Intersection:", set1.intersection(set2))
Output
Union: {1, 2, 3, 5, 7, 8, 9, 10}
Intersection: {3, 5}

Sets do not support indexing because they are unordered.

🔀 Conditional Statements

Conditional statements are used to make decisions based on conditions.

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
🎯 Key Insights

• Lists are ordered and mutable.
• Dictionaries store data as key-value pairs.
• Sets automatically remove duplicate values.
• append() adds one element, while extend() adds multiple elements.
• Indexing and slicing are used to access list elements.
• union() combines sets and intersection() finds common elements.
• if, elif, and else are used for decision-making.

📂 Project File

Python Data Structures - Lists, Dictionaries, Sets & Conditional Statements.ipynb

👩‍💻 Author

D. Suganya

Module 4 – Python Basics

Data Structures: Lists, Dictionaries, Sets & Conditional Statements
