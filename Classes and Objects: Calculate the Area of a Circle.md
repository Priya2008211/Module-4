# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

~~~
# Python program to calculate the area of a circle using class and object

class cse:
    def mech(self, r):
        area = 3.14 * r * r
        print("Area of Circle =", area)

# Get radius from user
radius = float(input("Enter the radius: "))

# Create object
obj = cse()

# Call method
obj.mech(radius)
~~~

## Output
~~~
Enter the radius: 5
Area of Circle = 78.5
~~~

## Result
The program is verified .
