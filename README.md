Project Title: Library Management System (LMS)
Overview:
The Library Management System (LMS) is a software application designed to manage and automate various tasks associated with a library. The system is intended for use by both library staff and users, offering functionalities for book management, user management, borrowing, and returning books. The project aims to provide an efficient way to track and manage books, users, and transactions, reducing the manual work required in a traditional library setting.

Objective:
To create a simple, user-friendly application in Java that helps in managing the day-to-day operations of a library, including:

Managing Books: Adding, removing, and updating book information.
Managing Users: Registering new users and viewing their details.
Borrowing and Returning Books: Facilitating users to borrow and return books while maintaining records of these transactions.
Tracking Book Availability: Displaying the current status of a book (available/borrowed).
Search Functionality: Allowing users to search books by title, author, or category.
Functionalities:
Admin Functions:

Add, edit, or delete book details (e.g., title, author, category, ISBN, quantity).
View a list of all available books in the library.
Add, edit, or delete user details (e.g., name, contact information, membership status).
View all users and their current borrowed books.
Issue books to users and track due dates.
Receive books back from users, update records, and track overdue books.
User Functions:

Register as a new user with personal details.
Search for books by title, author, or category.
View available books and check out books.
View a list of currently borrowed books and their due dates.
Return borrowed books to the library.
Search Functionality:

Users can search books by title, author, or category.
Admins can search for users by their name or user ID.
Transactions and Due Dates:

Books can be borrowed for a specified period (e.g., two weeks).
The system will track due dates and send reminders for overdue books.
Penalties can be applied to overdue books (optional feature).
Reporting:

Admins can generate reports showing books borrowed by each user.
Reports can show the number of available, borrowed, and overdue books.
Technologies Used:
Programming Language: Java
Database: MySQL or SQLite (for storing data related to users, books, and transactions)
GUI (Optional): JavaFX or Swing (for creating a graphical user interface)
File Handling: If you choose to implement file-based storage instead of databases (using CSV, XML, or JSON files).
IDE: IntelliJ IDEA, Eclipse, or NetBeans for development
Key Classes and Data Structures:
Book: Contains information about a book, such as title, author, ISBN, category, quantity, etc.
User: Contains information about a user, including their name, membership ID, contact details, and borrowed books.
LibraryManagementSystem: The main class that ties everything together, handling user interaction and calling necessary functions.
Admin: Responsible for administrative functions like adding/editing books and managing users.
Transaction: Manages the borrowing and returning of books, including tracking due dates and fines.
DatabaseHandler: Manages the interaction with the database (if using MySQL or SQLite).
System Flow:
Admin Flow:
Admin logs into the system.
Admin can add new books, edit existing books, and delete books from the system.
Admin can add new users and manage user details.
Admin can issue books to users, set due dates, and track overdue books.
Admin can return borrowed books and apply fines if applicable.
User Flow:
User registers in the system with their personal details.
User can search for books by title, author, or category.
User can borrow available books and receive due dates.
User can return books on or before the due date to avoid penalties.
User can view their borrowing history and due dates. 
