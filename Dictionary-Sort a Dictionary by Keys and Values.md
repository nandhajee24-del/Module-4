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
 

