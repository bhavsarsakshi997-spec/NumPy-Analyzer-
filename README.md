# My Project Title
﻿# NumPy-Analyzer

Project Explanation
1. Introduction

The NumPy Analyzer is a menu-driven Python program developed using the NumPy library. The main purpose of this program is to perform different operations on NumPy arrays.

The program allows the user to create 1D, 2D, and 3D arrays and perform operations such as indexing, slicing, mathematical calculations, combining, splitting, searching, sorting, filtering, and statistical calculations.

The program is divided into different functions, making it easy to understand, manage, and modify.

2. Definition of NumPy

NumPy stands for Numerical Python.

NumPy is a Python library used for numerical and scientific computing. It provides a powerful N-dimensional array object and many built-in functions for mathematical and statistical operations.

In this project, NumPy is mainly used for creating and manipulating arrays and performing calculations on array elements.

3. Module Used
NumPy Module

The following module is used in this program:
import numpy as np

Here, numpy is imported with the alias np.
The np alias is used throughout the program to access NumPy functions.

NumPy Functions Used in This Projectnp.array()
np.concatenate()
np.vstack()
np.array_split()
np.argwhere()
np.sort()
np.sum()
np.mean()
np.median()
np.std()
np.var()

4. Main Functions Used in the Program

The program is divided into the following user-defined functions:

4.1 create_array()

This function is used to create:
1. 1D Array
2. 2D Array
3. 3D Array

It takes the required number of elements from the user and creates a NumPy array using np.array().

For 2D and 3D arrays, reshape() is used to give the array the required dimensions.

4.2 indexing_slicing(arr)

This function performs:
1. Array Indexing
2. Array Slicing

It checks the dimension of the array using arr.ndim and performs indexing or slicing according to whether the array is 1D, 2D, or 3D.

4.3 mathematical_operations(arr)

This function performs mathematical operations between two arrays.

The operations are:
1. Addition
2. Subtraction
3. Multiplication
4. Division

The second array is created with the same shape as the original array.

4.4 combine_split_arrays(arr)

This function provides two operations:

Combine Arrays
1. np.concatenate() is used for 1D arrays.
2. np.vstack() is used for multidimensional arrays.

Split Array
1. np.array_split() is used to divide an array into multiple parts.

4.5 search_sort_filter(arr)

This function performs three operations:

1. Search :- np.argwhere() is used to find the position of a particular value.

2. Sort :- np.sort() is used to sort the array.

3. Filter :- Boolean filtering is used to select values according to a given condition.

Example :- arr[arr >= value]

4.6 aggregates_statistics(arr)

This function performs statistical operations on the array.

It calculates:
1. Sum
2. Mean
3. Median
4. Standard Deviation
5. Variance

The following NumPy functions are used:
np.sum()
np.mean()
np.median()
np.std()
np.var()

4.7 main()

The main() function controls the complete program.

It displays the main menu and allows the user to select different operations.

It also checks whether an array has been created before performing operations on it.

5. Python Concepts Used
5.1 Variables

Variables are used to store values temporarily.

Examples from the program:
1. choice
2. rows
3. columns
4. depth
5. elements
6. arr
7. second_array
8. result
9. value
10. parts

5.2 Functions

User-defined functions are used to divide the program into different modules.

Examples:
1. create_array()
2. indexing_slicing()
3. mathematical_operations()
4. combine_split_arrays()
5. search_sort_filter()
6. aggregates_statistics()
7. main()

This makes the program more organized and readable.

5.3 Conditional Statements

The program uses:
if ,elif ,else
Conditional statements are used to perform different operations according to the user's choice.

5.4 Loops

The program uses:
1. while loop :- while True is used to repeatedly display menus until the user chooses to exit.

2. for loop :- A for loop is used while displaying the different parts of a split array.

5.5 break Statement
The break statement is used to stop the loop when the user selects the Exit option.

5.6 return Statement
The return statement is used to return the created array from the create_array() function.

5.7 Exception Handling

The program uses:
try
except

Exception handling is used during the array splitting operation to prevent the program from stopping when an error occurs.

6. NumPy Array Concepts Used
6.1 1D Array

A one-dimensional array contains elements in a single row.

Example :- [10 20 30 40]

The program allows the user to create a 1D array.

6.2 2D Array

A two-dimensional array contains rows and columns.

Example :- [[10 20]
             [30 40]]

The program creates a 2D array using reshape().

6.3 3D Array

1. A three-dimensional array contains multiple rows, columns, and depth.
2. The program allows the user to create a 3D NumPy array.

6.4 Array Indexing

1. Indexing is used to access a particular element from an array.
2. The program supports indexing for 1D, 2D, and 3D arrays.

6.5 Array Slicing

1. Slicing is used to extract a specific portion of an array.
2. The program supports slicing according to the dimensions of the array.

6.6 Array Shape
T
1. he shape attribute is used to identify the dimensions of an array.
arr.shape
2. It is also used while creating the second array with the same shape as the original array.

6.7 Array Size

1. The size attribute gives the total number of elements in an array.
arr.size
2. It is used when taking elements for the second array.

6.8 Number of Dimensions

1. The ndim attribute gives the number of dimensions of an array.
arr.ndim
2. It is used to identify whether the array is 1D, 2D, or 3D.

7. Array Operations Used

The following array operations are implemented in the project:

1. Array Creation
2. Array Indexing
3. Array Slicing
4. Array Reshaping
5. Array Addition
6. Array Subtraction
7. Array Multiplication
8. Array Division
9. Array Combining
10. Array Splitting
11. Array Searching
12. Array Sorting
13. Array Filtering
14. Sum Calculation
15. Mean Calculation
16. Median Calculation
17. Standard Deviation
18. Variance Calculation

8. Advantages of NumPy
1. NumPy provides powerful array operations.
2. It supports multidimensional arrays.
3. Mathematical operations are easy to perform.
4. It provides many built-in mathematical and statistical functions.
5. It is useful for numerical calculations.

1. Input image :- <img width="676" height="752" alt="image" src="https://github.com/user-attachments/assets/f50c2f4d-7991-432b-b291-74db31d243e8" />

2. Output image :- <img width="387" height="272" alt="image" src="https://github.com/user-attachments/assets/5108587c-cfaf-448b-8859-ef240d2ea1d7" />


3. Video Link :-

9. Advantages of This Project
1. It is menu-driven and user-friendly.
2. It supports 1D, 2D, and 3D arrays.
3. It provides multiple array operations in one program.
4. It demonstrates important NumPy functions.
5. It provides mathematical and statistical operations.

10. Applications

NumPy is commonly used in:

1. Data Analysis
2. Data Science
3. Machine Learning
4. Scientific Computing
5. Mathematical Calculations
6. Statistical Analysis
7. Image Processing
8. Artificial Intelligence

11. Conclusion

The NumPy Analyzer project demonstrates the practical use of the NumPy library in Python. It covers array creation, indexing, slicing, mathematical operations, combining, splitting, searching, sorting, filtering, and statistical calculations.

The project also demonstrates important Python concepts such as functions, loops, conditional statements, exception handling, input/output, and array manipulation. Therefore, this project provides a simple and practical understanding of NumPy and its use in numerical data processing.


