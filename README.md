**Sparse Matrix Operations**

This Python project offers functionalities to perform arithmetic operations on sparse matrices. Sparse matrices are matrices that predominantly contain zero elements, and instead of storing all elements, only the non-zero elements and their positions are stored.

**Overview**

The project consists of a 'SparseMatrix' class for representing and manipulating sparse matrices, along with a main script for performing matrix operations such as addition, subtraction, and multiplication.

**SparseMatrix Class**

The 'SparseMatrix' class represents a sparse matrix and provides methods for initialization, loading from file, element access, arithmetic operations, and file output.

**Methods:**

*** + Initialization***: Initializes a sparse matrix object with optional parameters for dimensions and file path.

*** + Load from File***: Loads matrix data from a file.

*** + Element Access***: Retrieves or sets the value of an element at the specified row and column.

**Arithmetic Operations**:

***1. Addition***: Adds another sparse matrix to the current matrix.

***2. Subtraction***: Subtracts another sparse matrix from the current matrix.

***3. Multiplication***: Multiplies the current matrix by another sparse matrix.

File Output: Writes the matrix data to a file.

**Main Script**

The main script serves as the entry point for performing matrix operations. It accepts command-line arguments specifying paths to two matrix files and a directory to save the result. The user is prompted to choose an operation (addition, subtraction, or multiplication), and the result is saved to the specified directory.

**Usage**

Prepare Matrix Files: Create text files representing the sparse matrices. The first two lines should define the number of rows and columns. The following lines should list the non-zero elements in the format (row, col, value).
Run the Script: Execute the script with command-line arguments specifying the paths to the two matrix files and the directory to save the result.

**Requirements**

Python 3.x

**Getting Started**

Clone the repository.
Navigate to the project directory.
Run the main script with appropriate command-line arguments.

**Matrix File Format**
The matrix files should adhere to the following format:

The first line specifies the number of rows.
The second line specifies the number of columns.
Subsequent lines represent non-zero elements in the format (row, column, value).

**Example Format:**
scss
rows=3
cols=3
(0, 0, 1)
(1, 1, 2)
(2, 2, 3)
