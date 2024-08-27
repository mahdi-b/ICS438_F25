---
title: "Introduction to Python and Jupyter Notebook"
published: true
morea_id: experience-interactive-javascript-1
morea_type: experience
morea_summary: "Basic syntax: functions, for loops, while loops, if-then-else, arrays, objects"
morea_sort_order: 1
morea_start_date: "2021-07-13T23:00"
morea_labels:
---


### In-Class Assignment: Implementing OOP Concepts with File Handling

In this experience, you will start getting with Python Code in Analytics. As a team of 4-5 students, You will discuss offline the implementation details of a class that reads a TSV file and returns chunks of file.

**Objective:**  
You will create a Python class using inheritance to read and process data from a TSV (Tab-Separated Values) file. This assignment will help you understand inheritance and method overriding while working with large data files.

**Instructions:**

1. **Base Class Definition:**  
   - Create a base class called `FileReader`.
   - The class should take the file path as an argument during initialization and store it as an instance variable.
   - Implement a method called `read_file(self)` that reads the entire file into memory and returns it as a list of strings.

2. **Subclass Definition:**  
   - Create a subclass called `TSVReader` that inherits from `FileReader`.
   - **Override** the `read_file(self)` method in `TSVReader` to read the file in chunks instead of reading the entire file at once:
     - **`read_in_chunks(self, chunk_size)`**:
       - This method should read the file in chunks of `chunk_size` lines.
       - Return each chunk as a list of strings.
   - Add another method to `TSVReader`:
     - **`read_random_subset(self, k)`**:
       - This method should read a random subset of `k` lines from the file (excluding the header).
       - Return these lines as a list of strings.

3. **Example Use:**  
   - Demonstrate how to create an instance of `TSVReader` and use it to either get a random subset of lines or process the file in chunks.


**Key Concepts Covered:**
- **Inheritance**: Reuse common functionality from the base class (`FileReader`) in a subclass (`TSVReader`).
- **Method Overriding**: Customize the behavior of a method in a subclass by overriding it.
- **OOP Design**: Learn how to structure classes for better code organization and reusability.

