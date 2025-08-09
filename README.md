# Python List Manipulation Program

## 📌 Overview
This program demonstrates basic Python list operations such as appending, inserting, extending, removing, sorting, and finding the index of an element.  
It follows these steps:
1. Creates an empty list.
2. Appends elements to the list.
3. Inserts a value at a specific position.
4. Extends the list with another list.
5. Removes the last element.
6. Sorts the list in ascending order.
7. Finds and prints the index of a given value.

---

## 🖥️ Code Example
```python
# Create an empty list
my_list = []

# Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert at the second position
my_list.insert(1, 15)

# Extend with another list
my_list.extend([50, 60, 70])

# Remove last element
my_list.pop()

# Sort in ascending order
my_list.sort()

# Find index of value 30
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)
print("Final list:", my_list)
```

---

## 📊 Example Output
```
Index of 30: 4
Final list: [10, 15, 20, 30, 40, 50, 60]
```

---

## 🛠️ Requirements
- Python 3.x installed on your system.

---

## 🚀 How to Run
1. Save the Python code in a file, e.g., `list_operations.py`.
2. Open your terminal or command prompt.
3. Navigate to the directory where your file is saved.
4. Run the program:
   ```bash
   python list_operations.py
   ```
