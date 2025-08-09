#PLP Data Structures assignment

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
#creating an empty list called my_list
my_list = []

#appending elements to the list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

#insert value 15 at the second position (index 1)
my_list.insert(1, 15)

#extend my_list with another list: [50, 60, 70]
my_list.extend([50, 60, 70])

#remove the last element from my_list
my_list.pop()

#sort my_list in ascending order
my_list.sort()

#find and print the index of the value 30 in my_list
index_of_30 = my_list.index(30)
print("Index of 30 is: ", index_of_30)

print("The final list is: ", my_list)
```

---

## 📊 Example Output
```
Index of 30 is:  3
The final list is:  [10, 15, 20, 30, 40, 50, 60]
```

---

## 🛠️ Requirements
- Python 3.x installed on your system.

---

## 🚀 How to Run
1. Save the Python code in a file, e.g., `data_structures.py`.
2. Open your terminal or command prompt.
3. Navigate to the directory where your file is saved.
4. Run the program:
   ```bash
   python data_structures.py
   ```
