# Study-of-Lists-in-Python
## Aim:
To understand Python lists and perform operations such as indexing, slicing, and using built-in list methods.
## Objectives
-To create and access lists

-To perform indexing and slicing operations

-To apply commonly used list methods

-To understand mutable nature of lists

-To perform list traversal and modification
## Theory
### 1. Introduction to Lists
The true power of a Python list lies in its mutability and its dynamic nature. Unlike arrays in some other languages, a Python list doesn't require you to declare its size upfront or stick to a single data type. This means you can start with an empty list and grow it indefinitely as your program runs, mixing integers, strings, and even complex objects within the same structure. Because lists are stored as a sequence, they occupy a contiguous block of memory that allows Python to access any element near-instantaneously if you know its position, or "index."

This indexing system is incredibly flexible, supporting both forward and backward navigation. For instance, while index 0 always refers to the first element, Python also supports negative indexing, where -1 points to the very last item in the list. This makes it easy to grab the end of a data stream without needing to calculate the list's total length first. Furthermore, lists support a feature called slicing, which allows you to extract a specific "chunk" of the list by defining a start and end range. This is frequently used in data processing to strip headers or isolate specific segments of information.

Beyond just storing data, lists are equipped with a suite of built-in methods that make them highly functional for different programming patterns. You can use a list as a stack (Last-In, First-Out) by using the .append() and .pop() methods, or as a general-purpose container that you can reorder using .sort() or .reverse(). Because they allow duplicate values, they are the ideal choice for recording chronological events, such as a log of user actions or a history of price points, where the order of occurrence is just as important as the data itself.
The structure relies on zero-based indexing, which provides instant access to any element. Python also supports negative indexing, where -1 represents the last item, making it easy to reference the end of a collection. Additionally, slicing allows you to extract specific sub-sections of data effortlessly. Because lists maintain a strict order and allow duplicate values, they are the standard choice for handling sequences where the timeline or position of data is critical.
### 2. Characteristics of Python Lists
-Ordered: Elements maintain insertion order

-Indexed: Each element has a unique index starting from 0

-Mutable: Elements can be modified after creation

-Heterogeneous: Can store different data types in one list

-Allows Duplicates: Same value can appear multiple times
### 3.List Creation
Lists can be created in multiple ways:

-Using square brackets

-Using the list() constructor

Lists can also be nested, meaning a list can contain another list.
### 4. Indexing in Lists
Indexing allows access to individual elements of a list.
Types of Indexing

-Positive Indexing: Starts from 0 (left to right)

-Negative Indexing: Starts from -1 (right to left)

Element	A	B	C	D

Index	0	1	2	3

Negative Index	-4	-3	-2	-1
### 5. Slicing in Lists
Slicing is used to extract a portion (sublist) from a list.
General Syntax:
list_name[start : end : step]
Meaning of each part:

-start → index to begin slicing (included)

-end → index to stop slicing (excluded)

-step → gap between elements (optional)

Types of slicing:

-Beginning slice

-Ending slice

-Full slice

Slicing does not modify the original list.
### 6. Mutability of Lists
Lists are mutable, meaning their elements can be changed after creation.
Operations possible due to mutability:

-Updating elements

-Adding new elements

-Removing elements

This feature makes lists suitable for dynamic data storage.

### 7. List Traversal
Traversal means accessing each element of the list one by one.
Traversal can be done using:

-for loop

-while loop

Traversal is commonly used for data processing and analysis.

### 8. List Methods
Python provides several built-in methods to manipulate lists.
Method	Description

append()	Adds element at the end

insert()	Inserts element at given index

remove()	Removes specified element

pop()	Removes element by index

sort()	Sorts list

reverse()	Reverses list

clear()	Removes all elements

count()	Counts occurrences

index()	Returns index of element

### 9. Built-in Functions for Lists
Python provides built-in functions to work with lists:
Function	Purpose

len()	Number of elements

max()	Maximum value

min()	Minimum value

sum()	Sum of elements
## Problems:
### 1. Student Marks Management System
A teacher wants to store marks of students in a list.
Tasks:

>Create a list of student marks

>Display highest and lowest marks

>Calculate average marks

>Sort the marks in ascending order

Concepts Used: List creation, max(), min(), sum(), len(), sort()

### 2. Grocery Shopping List
A user maintains a grocery list for monthly shopping.
Tasks:

>Create a grocery list

>Add new items to the list

>Remove purchased items

>Display the final shopping list

Concepts Used: append(), remove(), indexing

### 3. Attendance Register
A class teacher records daily attendance.
Tasks:

>Store present student roll numbers in a list

>Check whether a particular student is present

>Count total students present

Concepts Used: in operator, count(), len()

### 4. Mobile Contact List
A person stores phone contacts in a list.
Tasks:

>Create a list of contacts

>Add a new contact

>Delete an existing contact

>Display contacts alphabetically

Concepts Used: append(), remove(), sort()

### 5. Temperature Analysis
Daily temperature readings of a city are stored in a list.
Tasks:

>Display temperatures of first and last 5 days

>Find highest and lowest temperature

>Calculate average temperature

Concepts Used: Slicing, max(), min(), sum()

