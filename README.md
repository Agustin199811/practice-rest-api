# Spring Boot Book REST API

This Spring Boot book REST API provides endpoints to manage book information, such as retrieving all books, creating new books, updating existing book information, and deleting books.

## Project Status

This project is currently in development and is being worked on for version 1.0.0.

## Installation and Setup

1. Clone this repository to your local machine using the following command:
git clone https://github.com/Agustin199811/practice-rest-api.git

3. Import the project into your preferred IDE (e.g., IntelliJ IDEA or Eclipse) as a Maven project.

4. Configure the MySQL database in your local environment. You can find instructions for configuring the database in the `application.properties` file.
# Changes in your project in the databsase

- `spring.datasource.url=jdbc:mysql://localhost:3306/rest_api_book`
- `spring.datasource.username=root`
- `spring.datasource.password=root`

5. Run the Spring Boot application. The application will be available at `http://localhost:8081`.

## Usage

The book REST API exposes the following endpoints:

- `GET /api/books`: Get all books.
- `GET /api/books/{id}`: Get a book by its ID.
- `POST /api/books`: Create a new book.
- `PUT /api/books/{id}`: Update existing book information.
- `DELETE /api/books/{id}`: Delete a book by its ID.

You can use tools such as Postman or cURL to send HTTP requests to these endpoints.

## API Documentation

API documentation is available in Swagger. You can access it at `http://localhost:8081/swagger-ui.html`.

## Contribution

If you wish to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b my-new-feature`.
3. Make your changes and commit them: `git commit -am 'Add a new feature'`.
4. Push your changes to your forked repository: `git push origin my-new-feature`.
5. Create a new pull request and describe your changes in detail.

## License

This project is licensed under the MIT License. You can find more information in the `LICENSE` file.

## Contact

If you have any questions or suggestions, feel free to contact the development team at (toapantaagustin9c@gmail.com).

## Acknowledgements

We would like to thank the open-source community for their ongoing support and contributions to this project.

Thank you for using our Spring Boot book REST API!

## Create By 
Patricio Agustin Toapanta Acosta