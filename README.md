Nandha A(25017364)

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

## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```py
# Step 1: Define two dictionaries
dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}

# Step 2: Define the merge function
def merge(d1, d2):
    return {**d1, **d2}

# Step 3: Call the function and print the result
merged_dict = merge(dict1, dict2)
print("Merged Dictionary:", merged_dict)
```

## Output
<img width="696" height="76" alt="Screenshot 2025-10-22 214619" src="https://github.com/user-attachments/assets/85bf733e-6ab3-4563-bc4e-d8fcd6701ea0" />

## Result
successfully  Python program that merges **two dictionaries** and combines their key-value pairs. 

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
```py
# Step 1: Start the program

# Step 2: Define a dictionary
data = {'banana': 3, 'apple': 5, 'cherry': 2, 'date': 4}

# Step 3: Sort by keys
sorted_by_keys = dict(sorted(data.items()))

# Step 4: Sort by values
sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))

# Step 5: Display results
print("Original Dictionary:", data)
print("Sorted by Keys:", sorted_by_keys)
print("Sorted by Values:", sorted_by_values)

# Step 6: End the program
```

## Sample Output
<img width="751" height="132" alt="Screenshot 2025-10-22 214903" src="https://github.com/user-attachments/assets/74c16444-7a5f-45b2-b7f1-30374e1a2914" />

## Result
successfully  Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order
 

 # Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```py
# Step 1: Define the list
list1 = [10, 20, 30]

# Step 2: Try to access an out-of-range index
try:
    print("Accessing index 5:", list1[5])
except IndexError:
    print("You're out of list range")

# Step 3: Program continues gracefully
print("Program completed.")
```

## Output
<img width="576" height="89" alt="Screenshot 2025-10-22 215101" src="https://github.com/user-attachments/assets/d5cfa650-bbfe-498b-9797-8eea1ab94a7b" />

## Result
sauccessfully Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.
 
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
```py
with open('story.txt', 'w') as file:
    file.write("This is the first line.\n")
    file.write("Another line begins here.\n")
    file.write("Totally tubular text.\n")
    file.write("hello world.\n")
    file.write("Testing again.\n")
    file.write("Final line.\n")

count = 0
with open('story.txt', 'r') as file:
    for line in file:
        stripped = line.lstrip()
        if stripped and stripped[0] != 'T':
            count += 1

print("Number of lines not starting with 'T':", count)
```

## Output
<img width="802" height="397" alt="image" src="https://github.com/user-attachments/assets/7023db77-c793-4a8a-8000-9c22dd555cb5" />

## Result
successfully Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.
