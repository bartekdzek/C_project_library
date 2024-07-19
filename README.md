# C_project_library
Library project in C



### Book Database Management System

This project is a simple book database management system written in C. It allows users to manage a collection of books, including adding, displaying, searching, deleting, and sorting books. The database is stored in a binary file, which ensures data persistence between program runs.

#### Features

1. **Add Book**
   - Users can add new books to the database. Each book has the following attributes:
     - Title
     - Author
     - Year of publication
     - Type of cover (e.g., hardcover, paperback)
     - Number of pages
     - Type of book (e.g., novel, textbook)

2. **Display Books**
   - Users can display all books currently in the database in a tabular format.

3. **Search Books**
   - Users can search for books by:
     - Author's name
     - Keyword in the title

4. **Delete Book**
   - Users can delete a book from the database by specifying its index.

5. **Sort Books**
   - Users can sort the books by:
     - Author's name
     - Title

6. **Data Persistence**
   - The database is stored in a binary file, allowing data to persist between program runs.

#### Implementation Details

- **Data Structures**
  - `Ksiazka`: A structure to store information about a single book.
  - `BazaKsiazek`: A structure to store the array of books and the number of books in the database.

- **Memory Management**
  - Dynamic memory allocation is used to manage the array of books. Functions like `realloc` are used to resize the array as books are added or removed.

- **File Operations**
  - The program uses file I/O to read from and write to a binary file (`baza.bin`) to persist the database.

- **User Interface**
  - The program provides a simple text-based menu for users to interact with the system. The menu includes options for adding, displaying, searching, deleting, and sorting books.


This project demonstrates fundamental C programming concepts such as dynamic memory allocation, file I/O, and basic data structures. It provides a solid foundation for understanding more complex database management systems and can be extended with additional features such as advanced search capabilities, graphical user interface, or integration with SQL databases.
