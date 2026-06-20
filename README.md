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
