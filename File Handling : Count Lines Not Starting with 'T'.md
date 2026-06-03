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
~~~
# Python program to count lines not starting with 'T'

# Open the file in read mode
file = open("story.txt", "r")

count = 0

# Read each line from the file
for line in file:
    # Check if line does not start with 'T'
    if not line.startswith('T'):
        count += 1

# Display the result
print("Number of lines not starting with 'T' =", count)

# Close the file
file.close()
~~~
## Output
~~~
Number of lines not starting with 'T' = 3
~~~

## Result
The program is verified.
