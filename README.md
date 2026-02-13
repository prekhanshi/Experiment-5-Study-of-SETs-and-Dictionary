# Experiment-5-Study-of-SETs-and-Dictionary
# Study of Python Sets and Dictionaries: Operations and Applications
# Experiment Overview
This experiment (Experiment 5) focuses on two essential Python data structures: Sets and Dictionaries. The objective is to understand their unique properties—such as uniqueness in sets and key-value mapping in dictionaries—and to implement various operations like mathematical set logic, data retrieval, and record updating. These structures are vital for Exploratory Data Analysis (EDA) and efficient data management.

# Name: PREKHANSHO KUMBHAKAR

# PRN: 25070123149

# Branch: ENTC A1

# Theoretical Background: Python Sets
Introduction to Sets A Set is an unordered collection of items where every element is unique. Sets are written with curly brackets {}. They are particularly useful when the presence of an item matters more than its order or frequency.

 Key Properties of Sets Unordered: Set items do not have a defined order; they may appear in different orders every time you use them and cannot be referred to by an index.

 Unique Elements: Sets automatically handle duplicates. If the same value is added twice, the set will only store it once.

 Mixed Data Types: A single set can contain various data types, including strings, integers, and boolean values.

 Boolean Equivalence: In Python sets, the values True and 1 are considered the same value and are treated as duplicates.

Set Operations and Logic The experiment covers mathematical operations that are fundamental to set theory:
Union (|): Combines all elements from both sets.

Intersection (&): Returns only the elements present in both sets.

Difference (-): Returns elements present in the first set but not the second.

Symmetric Difference (^): Returns elements present in either of the sets, but not both.

Frozen Sets A frozenset is an immutable version of a Python set. While standard sets allow for the addition or removal of elements, a frozenset's content cannot be modified after creation, providing a "read-only" version of the data.
Theoretical Background: Python Dictionaries
Introduction to Dictionaries A Dictionary is a collection used to store data values in key:value pairs. It is ordered (as of Python 3.7+), changeable, and does not allow duplicate keys.

Key Properties of Dictionaries Key-Value Mapping: Data is retrieved by referring to its unique key rather than an index number.

Uniqueness of Keys: If a dictionary is created with duplicate keys, the last value assigned to that key will overwrite the previous ones.

# Mutability: You can change, add, or remove items after the dictionary has been created.

Core Dictionary Operations Retrieval: Using methods like .get() to find values or handle cases where a key might not exist.
Modification: Adding new pairs or updating existing values by referencing the key.

# Removal: Using .pop() to delete specific key-value pairs from the structure.

Practical Scenarios Covered
Set Applications Duplicate Removal: Converting a list of event participants into a set to automatically filter out accidental duplicate registrations.

Common Interest Identification: Using intersections to find elective subjects chosen by multiple students.

Club Membership Analysis: Using set logic to identify students belonging to both cricket and football clubs versus those in only one.

# Dictionary Applications Inventory Management: Storing product names and prices to allow for quick price updates.

# User Authentication: Validating login credentials by matching usernames (keys) with passwords (values).

# Performance Analysis: Identifying a "topper" by searching for the maximum value in a dictionary of student marks.

# Conclusion
Through this experiment, the distinct advantages of Sets and Dictionaries were demonstrated:

Sets are the most efficient tool for ensuring data uniqueness and performing complex group comparisons (like intersections and differences).

Dictionaries provide a powerful way to organize data logically, allowing for rapid lookups and structured data storage that mimics real-world records.

Immutability Control: The use of frozenset highlights Python's ability to protect data integrity when constant, unchangeable collections are required.

Overall, mastering these structures is essential for handling complex data relationships and improving the performance of search and filter operations in Python.
