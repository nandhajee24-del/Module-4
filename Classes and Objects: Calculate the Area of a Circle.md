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
```py
import math

# Step 2: Define the class
class cse:
    # Step 3: Define the method
    def tech(self, radius):
        area = math.pi * radius ** 2
        return area

# Step 1: Get user input
r = float(input("Enter the radius of the circle: "))

# Step 4: Execute the program
circle = cse()
result = circle.tech(r)
print(f"The area of the circle is: {result:.2f}")
```


## Output
<img width="377" height="74" alt="Screenshot 2025-10-22 214324" src="https://github.com/user-attachments/assets/1f96d2d2-2f4f-476b-8419-4279ffcf8e39" />

## Result
successfully Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.
