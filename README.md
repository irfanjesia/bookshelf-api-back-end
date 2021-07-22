# 📃 Description
This project is my submission for Dicoding Learn to Make Back-End Apps for Beginners Course. It is is required to use NodeJS the Hapi framework.
Dicoding provided Postman Collection and Environment files for testing at the following [link](https://github.com/dicodingacademy/a261-backend-pemula-labs/raw/099-shared-files/BookshelfAPITestCollectionAndEnvironment.zip).

Here are the criterias:
- The API you create should be able to store books via method POST. URL : /books
- The API you create should be able to display all the books stored via method GET. URL: /books
- The API you create should be able to display all the books stored via method GET. URL: /books/{bookId}
- The API you create must be able to change book data based on id via method PUT. URL: /books/{bookId}
- The API you create should be able to delete books by id via method DELETE. URL: /books/{bookId}
- Bookshelf API projects must meet all automated tests on Postman requests marked **Mandatory**.

For this project i added query parameters `?name`, `?reading` and `?finished` to the GET /books route, applied CORS to all existing resources, and used ESLint and one of the style guides (AirBnB) to make JavaScript code more consistent. And for the id, i used nanoid.
