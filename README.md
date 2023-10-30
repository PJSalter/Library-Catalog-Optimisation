# 📚 Library Catalog Optimization

### 📖 A Library Book Sorting Application

## Overview

This C++ project 📊 manages a sorted list of books implemented using a linked list (LinkedListLibrary) and the same list implemented using a vector (VectorLibrary). Each list contains 100 books, sorted in ascending order by ISBN number. 📖📚 The primary goal is to insert a new book into both the linked list and the vector and output the number of operations required for each insertion. 🚀

## Project Structure

The project includes the following key components:

- `main.cpp`: The 🏗️ main program that orchestrates the book insertion process and reports the number of operations for both the linked list and vector. 📦

- `LinkedListLibrary.h` and `LinkedListLibrary.cpp`: The linked list implementation, including insertion and destruction methods. 📦

- `VectorLibrary.h` and `VectorLibrary.cpp`: The vector implementation, including insertion and printing methods. 📈

- `BookNode.h` and `BookNode.cpp`: A class representing individual book nodes used in the linked list. 📖

- `Book.h` and `Book.cpp`: A class representing books with attributes such as title, author, and ISBN. 📕

## How to Compile and Run

To compile and run the project, follow these steps:

1. Ensure you have a C++ development environment set up, such as a C++ compiler (e.g., g++). 🛠️

2. Clone or download this repository to your local machine. 📦

3. Open a terminal or command prompt and navigate to the project directory. 🖥️

4. Compile the C++ code:

   ```bash
   g++ LinkedListLibrary.cpp VectorLibrary.cpp BookNode.cpp Book.cpp main.cpp -o BookSortingApp
   ```

5. Run the executable: 🚀

   ```bash
   ./BookSortingApp
   ```

6. Observe the output, which will display the number of operations required to insert a new book into both the linked list and the vector. 📊

## Example Input

```
The Catcher in the Rye
9787543321724
J.D. Salinger
```

## Example Output

```
Number of linked list operations: 1
Number of vector operations: 1
```

## Conclusion

This C++ Application provides a simple comparison of insertion operations between a linked list and a vector data structure. It offers a basic illustration of how different data structures can impact the efficiency of operations like insertion. 🧐
