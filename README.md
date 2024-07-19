Book Database Management System
Overview
The Book Database Management System is a Java-based application designed to facilitate the management of a collection of books using International Standard Book Numbers (ISBNs). This program allows users to perform essential operations such as adding books to the database, searching for books by ISBN to check their availability, and printing a list of all ISBNs currently stored in the system. It provides a straightforward command-line interface (CLI) for user interaction, making it accessible for managing personal or small-scale book collections.

Features
1. Add Book
Users can add a new book to the database by entering a valid ISBN. The program validates the ISBN format (either 10 or 13 digits) and adds it to the collection if the database capacity allows.

2. Search ISBN
The search functionality allows users to check whether a specific ISBN is already present in the database. If the ISBN is found, the program confirms its existence; otherwise, it notifies the user that the ISBN is not in the database.

3. Print All ISBNs
This feature displays a list of all ISBNs currently stored in the database. It provides a quick overview of the entire collection and helps users manage their inventory effectively.

4. Exit
Users can terminate the program gracefully using the exit option from the menu, ensuring a smooth user experience.

Getting Started
To run the Book Database Management System on your local machine, follow these steps:

Prerequisites:

Java Development Kit (JDK) installed on your computer.
Git installed (optional for cloning the repository).
Clone the Repository:

bash
Copy code
git clone <repository-url>
cd <repository-directory>
Compile the Program:
Navigate to the directory containing BookDatabase.java and compile it using the Java compiler.

bash
Copy code
javac BookDatabase.java
Run the Program:
Execute the compiled Java program.

bash
Copy code
java BookDatabase
Interact with the Program:
Follow the on-screen instructions to add books, search by ISBN, print all ISBNs, and exit the program.

Example Usage
Here's an example scenario illustrating the usage of the Book Database Management System:

Adding a Book:

vbnet
Copy code
Enter ISBN to add: 9780141439570
ISBN added to database.
Searching for ISBN:

css
Copy code
Enter ISBN to search: 9780141439570
ISBN found in database.
Printing All ISBNs:

css
Copy code
All ISBNs in database:
9780141439570
9780061120084
9780307594005
License
This project is licensed under the MIT License. See the LICENSE file for more details.

