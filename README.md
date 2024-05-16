# Book Recommendations Python Script

This Python script allows users to search for books by genre or author from a database stored in an Excel file ('books.xlsx'). It randomly selects a matching book and displays its details.

## Usage
1. Make sure 'books.xlsx' file exists in the same directory as the script.
2. Run the script. It will prompt you to choose a book by genre or author.
3. Enter your choice, and the script will display details of a randomly selected matching book.

## Requirements
- Python 3.x
- openpyxl library (install using `pip install openpyxl`)

## How It Works
1. The script loads book information from 'books.xlsx' using openpyxl.
2. It prompts the user to input a genre or author for book search.
3. It filters the list of books based on the user input.
4. If matching books are found, it randomly selects one and displays its details.

## Function Reference
- `search_book()`: Prompts user input for book search and selects a random matching book.
- `read_book_file(books_file)`: Reads book information from 'books.xlsx' file and returns a list of books.
- `printing_info(result)`: Prints details of a book to the console.

## Notes
- Ensure 'books.xlsx' contains book information with columns for title, author, genre, and description.

This README provides a brief overview of the script, how to use it, its requirements, and how it works. For more detailed documentation, refer to the comments within the script or additional documentation files if provided.
