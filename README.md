# Library Management System

## Author
Abdelrahman Ahmed Elkhmisi

## Project Description

Library Management System is a Python desktop application connected to an SQLite database.

The system allows users to manage:
- Books
- Members
- Borrowing records

The project includes a graphical user interface (GUI) built with Tkinter and stores all information using SQLite.

## Technologies Used

- Python
- SQLite
- Tkinter
- GitHub

## Features

### Book Management
- Add books
- Update books
- Delete books
- View books

### Member Management
- Add members
- Update members
- Delete members
- View members

### Borrowing System
- Borrow books
- Return books
- Manage borrowing records

## Database Design

The application uses SQLite with three main tables:

### Books
Stores book information:
- ID
- Title
- Author
- Availability status

### Members
Stores member information:
- ID
- Name
- Email

### Borrowings
Stores borrowing transactions:
- ID
- Book ID
- Member ID
- Borrow date
- Return date

## Project Structure


Library-Management-System/

├── main.py
├── database.py
├── README.md


## How to Run

1. Install Python.

2. Download the project.

3. Open the project folder.

4. Run:


python main.py


The database will be created automatically when the application starts.

## Development Process

The project was developed step by step:

1. Designed the database structure.
2. Created SQLite tables.
3. Developed database functions.
4. Created the graphical interface using Tkinter.
5. Added CRUD operations.
6. Tested the application and fixed errors.

## Challenges

During development, some challenges included connecting the GUI with the database, handling database operations, and improving the user interface.

These problems were solved by testing each function separately and improving the code structure.

## What I Learned

Through this project, I improved my knowledge of:

- Python programming
- SQL database management
- GUI development
- GitHub version control
- Software development workflow
