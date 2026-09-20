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
```
numbers = [10, 20, 30, 40, 50]
try:
    index = int(input("Enter the index to access: "))
    print("Element at index", index, "is", numbers[index])

except IndexError:
    print("Error: Index out of range! Please enter a valid index.")
```

## Output
<img width="1182" height="317" alt="image" src="https://github.com/user-attachments/assets/241b6804-0c7e-4a42-8d81-9a3c7be98745" />

## Result
The code executed successfully.
