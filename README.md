# BookshelfAPI

This is a simple REST API to manage a collection of books. It allows you to add, update, delete, and fetch books from memory storage.

## Endpoints

- `POST /books` : Add a new book
- `GET /books` : Retrieve all books
- `GET /books/{bookId}` : Get details of a specific book
- `PUT /books/{bookId}` : Update a book by its ID
- `DELETE /books/{bookId}` : Delete a book by its ID

## Installation

1. Clone the repository
2. Run `npm install` to install dependencies
3. Run `npm start` to start the server on port 9000