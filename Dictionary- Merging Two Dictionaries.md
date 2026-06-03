## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
~~~
# Python program to merge two dictionaries

# Define dictionaries
dict1 = {
    "a": 10,
    "b": 20,
    "c": 30
}

dict2 = {
    "d": 40,
    "e": 50,
    "b": 100
}

# Function to merge dictionaries
def merge(dict1, dict2):
    merged_dict = {**dict1, **dict2}
    return merged_dict

# Function call
result = merge(dict1, dict2)

# Display output
print("Merged Dictionary:", result)
~~~

## Output
~~~
Merged Dictionary: {'a': 10, 'b': 100, 'c': 30, 'd': 40, 'e': 50}
~~~

## Result
The program is verified.
