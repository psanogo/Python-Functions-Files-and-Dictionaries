# Python Assignment: Functions, Files, and Dictionaries

## 🎯 Objective

This assignment is designed to strengthen your understanding of fundamental Python concepts. You will practice creating and using functions, reading from and writing to files, and manipulating data using dictionaries.

---

## 📚 Core Concepts

*   **Functions**: Learn to define and call your own functions to create modular, reusable, and organized code.
*   **File Handling**: Practice opening, reading, processing, and writing data to text files.
*   **Dictionaries**: Use dictionaries to store and retrieve data in key-value pairs, a powerful way to manage structured information.

---

## 🚀 Instructions

1.  Review the problem descriptions in the assignment notebook or script.
2.  Implement the required functions and logic in the designated code cells or files.
3.  Ensure your code is well-commented and follows good programming practices.
4.  Test your solutions with the provided examples to verify they work as expected.

---

## ✨ Key Concepts with Examples

### Functions
A function is a block of code that only runs when it is called. They help break our program into smaller and modular chunks.

```python
def greet(name):
    """This function greets the person passed in as a parameter."""
    return f"Hello, {name}!"

# Calling the function
print(greet("World"))
```

### File Handling
Python has built-in functions for creating, reading, updating, and deleting files. The `with` statement is the recommended way to handle file objects.

```python
# Writing to a file (creates the file if it doesn't exist)
with open("example.txt", "w") as f:
    f.write("This is a sample file.\n")
    f.write("It contains two lines.\n")

# Reading from a file
with open("example.txt", "r") as f:
    content = f.read()
    print(content)
```

### Dictionaries
Dictionaries are used to store data values in `key:value` pairs. They are mutable, ordered (as of Python 3.7), and do not allow duplicate keys.

```python
# Creating and using a dictionary
student_grades = {
    "Alice": 88,
    "Bob": 95,
    "Charlie": 72
}

# Accessing a value by its key
print(f"Bob's grade: {student_grades['Bob']}")

# Adding a new entry
student_grades["David"] = 99
print(student_grades)
```

