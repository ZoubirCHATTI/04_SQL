# SQL Basics: A Synthetic Library Management System

This project demonstrates fundamental SQL operations using Python and SQLite to manage a synthetic library database. The script, `SQL_BASICS.ipynb`, creates a database, populates it with book data, and allows for various queries to be performed.

## Features

* **Database Creation:** Initializes an SQLite database named `library.db` and a `book` table to store library data.
* **Data Insertion:** Populates the `book` table with a synthetic dataset of 10 books, including details like title, author, publication date, and availability.
* **Data Retrieval:**
    * Finds all available books written by a specific author.
    * Searches for books published before a user-specified date.
    * Identifies a book's name and availability status based on its ID.
* **Interactive Queries:** Prompts the user for input to perform dynamic searches and data analysis, such as counting the number of books that meet certain criteria.
* **Basic Data Analysis:** Uses the `COUNT` function to determine the number of books that fit specific criteria, such as the total number of available books.

## How to Run the Script

1.  Make sure you have Python installed on your system.
2.  The script uses the built-in `sqlite3` library, so no additional installations are required.
3.  Run the script from your terminal:
    ```bash
    python sql_basics.py
    ```
4.  Follow the on-screen prompts to interact with the library database.
    
  Or use the google.colab badge on the top of the notebook to run it in colab
## Technologies Used

* **Python:** The core programming language for scripting and database interaction.
* **SQLite:** A C-language library that implements a small, fast, self-contained, high-reliability, full-featured SQL database engine.