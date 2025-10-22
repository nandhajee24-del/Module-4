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
 
