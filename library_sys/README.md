# Simple Library System 


Python program for managing a simple library system. We'll break down the functionality into different modules for better organization and reusability.

## structure of our modular library system:

1) Main Program (main.py):

This will be the main entry point of our program where we interact with users and call functions from other modules.

2) Book Module (book.py):

This module will define a Book class to represent a book.
It will contain functions for adding, removing, and retrieving information about books.

3) Member Module (member.py):

This module will define a Member class to represent a library member.
It will contain functions for adding, removing, and retrieving information about members.

4) Library Module (library.py):

This module will handle operations related to the library system, such as borrowing and returning books, checking availability, etc.
It will interact with the Book and Member modules.