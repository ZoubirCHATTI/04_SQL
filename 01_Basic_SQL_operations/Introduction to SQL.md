{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyMtZ+8BjRaGX2OTgQcaMV0q",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/ZoubirCHATTI/04_SQL/blob/main/01_Basic_SQL_operations/Introduction%20to%20SQL.md\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "# SQL Basics: A Synthetic Library Management System\n",
        "\n",
        "This project demonstrates fundamental SQL operations using Python and SQLite to manage a synthetic library database. The script, `SQL_BASICS.ipynb`, creates a database, populates it with book data, and allows for various queries to be performed.\n",
        "\n",
        "## Features\n",
        "\n",
        "* **Database Creation:** Initializes an SQLite database named `library.db` and a `book` table to store library data.\n",
        "* **Data Insertion:** Populates the `book` table with a synthetic dataset of 10 books, including details like title, author, publication date, and availability.\n",
        "* **Data Retrieval:**\n",
        "    * Finds all available books written by a specific author.\n",
        "    * Searches for books published before a user-specified date.\n",
        "    * Identifies a book's name and availability status based on its ID.\n",
        "* **Interactive Queries:** Prompts the user for input to perform dynamic searches and data analysis, such as counting the number of books that meet certain criteria.\n",
        "* **Basic Data Analysis:** Uses the `COUNT` function to determine the number of books that fit specific criteria, such as the total number of available books.\n",
        "\n",
        "## How to Run the Script\n",
        "\n",
        "1.  Make sure you have Python installed on your system.\n",
        "2.  The script uses the built-in `sqlite3` library, so no additional installations are required.\n",
        "3.  Run the script from your terminal:\n",
        "    ```bash\n",
        "    python sql_basics.py\n",
        "    ```\n",
        "4.  Follow the on-screen prompts to interact with the library database.\n",
        "    \n",
        "  Or use the google.colab badge on the top of the notebook to run it in colab\n",
        "## Technologies Used\n",
        "\n",
        "* **Python:** The core programming language for scripting and database interaction.\n",
        "* **SQLite:** A C-language library that implements a small, fast, self-contained, high-reliability, full-featured SQL database engine."
      ],
      "metadata": {
        "id": "3DLMKwl429rO"
      }
    }
  ]
}