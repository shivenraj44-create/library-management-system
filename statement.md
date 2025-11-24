 Project Statement

 1. Problem Statement
Traditional manual methods of managing library records using physical registers are inefficient, time-consuming, and prone to human error. Librarians often struggle to track which books are currently available versus those that have been borrowed, leading to inventory mismanagement. Furthermore, physical records are susceptible to damage or loss, posing a risk to the integrity of library data. There is a need for a digital solution to automate these tasks and ensure data persistence.

 2. Scope of the Project
The scope of this project is to develop a *Console-Based Library Management System* using Python. The system is designed to streamline the fundamental operations of a library, including inventory management and transaction tracking.

Technical Scope:
Core Logic: Implements Object-Oriented Programming (OOP) concepts (Classes, Objects) to model Books and the Library system.
  Data Persistence:Utilizes File Handling (Text/CSV) to ensure data is saved and retrieved effectively, preventing data loss when the program terminates.
  Interface: Features a modular, menu-driven Command Line Interface (CLI) for ease of use.

 3. Target Users
Librarians / Administrators: The primary users who need to add new books to the system, update the inventory, and issue books to students.
  Students / Faculty: The beneficiaries who gain access to an organized view of available books and experience a faster borrowing/returning process.

 4. High-Level Features
Book Management: Functionality to add new books with details (ID, Title, Author) to the system catalog.
Inventory Tracking: A "View All" feature that displays the complete list of books and their current status (Available/Borrowed).
Borrowing System: Allows users to check out a book, automatically updating its status to "Borrowed" in the database.
Return System: Allows users to return books, instantly updating the status back to "Available."
Data Persistence: Automatic saving and loading of library records using file handling techniques to ensure long-term storage.
Input Validation: Robust error handling to manage invalid inputs (e.g., entering empty data or non-existent Book IDs).
