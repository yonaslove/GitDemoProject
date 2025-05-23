Debre Birhan University Library Management System
A command-line based library management system designed for Debre Birhan University, supporting student login/registration, book management, borrowing, and returning functionality. Built with Python.
Features
👤 For Students:
Register with name, ID number, and password.

Login using username and password.

View all available books.

Search for a specific book.

Borrow books (only one at a time).

Return borrowed books and see late return charges (calculated per hour).

🛠️ For Recorders (Admins):
Secure access via password.

Add new books with publication date and quantity.

View list of all books.

Check availability status.

Search and delete books.

Modify book attributes (shelf number, quantity).

Register new students.

🗃️ File Structure
students.txt – Stores student info (username:name:id_no:password).

books.txt – Stores book info (book_name:author:id:shelf_no:status:pub_date:quantity).

borrowed_books.txt – Logs borrowed books and timestamps (book_name:...borrowed_by:...borrow_date:...).

💻 How to Run
Install Python
Ensure Python 3.6+ is installed on your machine.

Clone this repository or copy the script

Run the application

bash

    python main.py

Follow the menu

Press 1 to log in as student

Press 2 to log in as recorder (password: 123)
