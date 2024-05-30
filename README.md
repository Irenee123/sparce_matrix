parse Matrix Operations
This Python project offers functionalities to perform arithmetic operations on sparse matrices. Sparse matrices are matrices that predominantly contain zero elements, and instead of storing all elements, only the non-zero elements and their positions are stored.

Overview
The project consists of a SparseMatrix class for representing and manipulating sparse matrices, along with a main script (script.py) for performing matrix operations such as addition, subtraction, and multiplication.

SparseMatrix Class
The SparseMatrix class represents a sparse matrix and provides methods for initialization, loading from file, element access, arithmetic operations, and file output.

Methods:
__init__(self, numRows=None, numCols=None, matrixFilePath=None): Initializes a sparse matrix object with optional parameters for dimensions and file path.
load_from_file(self, filePath): Loads matrix data from a file.
get_element(self, currRow, currCol): Retrieves the value of an element at the specified row and column.
set_element(self, currRow, currCol, value): Sets the value of an element at the specified row and column.
Arithmetic Operations:
add(self, other): Adds another sparse matrix to the current matrix.
subtract(self, other): Subtracts another sparse matrix from the current matrix.
multiply(self, other): Multiplies the current matrix by another sparse matrix.
to_file(self, filePath): Writes the matrix data to a file.
Main Script (script.py)
The script.py file serves as the entry point for performing matrix operations. It accepts command-line arguments specifying paths to two matrix files and a directory to save the result. The user is prompted to choose an operation (addition, subtraction, or multiplication), and the result is saved to the specified directory.
