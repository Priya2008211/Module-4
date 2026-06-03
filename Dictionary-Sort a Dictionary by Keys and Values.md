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
~~~
# Python program to sort a dictionary by keys and values

# Define dictionary
student = {
    "Ravi": 85,
    "Anu": 92,
    "Kiran": 78,
    "Divya": 88
}

# Display original dictionary
print("Original Dictionary:")
print(student)

# Sort dictionary by keys
sorted_keys = dict(sorted(student.items()))

# Sort dictionary by values
sorted_values = dict(sorted(student.items(), key=lambda item: item[1]))

# Display sorted dictionaries
print("\nDictionary Sorted by Keys:")
print(sorted_keys)

print("\nDictionary Sorted by Values:")
print(sorted_values)
~~~

## Sample Output
~~~
Original Dictionary:
{'Ravi': 85, 'Anu': 92, 'Kiran': 78, 'Divya': 88}

Dictionary Sorted by Keys:
{'Anu': 92, 'Divya': 88, 'Kiran': 78, 'Ravi': 85}

Dictionary Sorted by Values:
{'Kiran': 78, 'Ravi': 85, 'Divya': 88, 'Anu': 92}
~~~

## Result
The program is verified.

