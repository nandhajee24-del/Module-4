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
