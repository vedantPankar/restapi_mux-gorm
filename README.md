# User Management API

This is a simple RESTful API for managing users using Go, Gorilla Mux, and Gorm with MySQL.

## Prerequisites

- Go 1.16+
- MySQL

## Installation

1. Clone the repository and navigate into it.
2. Install the required Go dependencies.
3. Set up a MySQL database named `testdb` and update the DSN in the code if necessary.

## Usage

1. Run the application using `go run main.go`.
2. Use the following API endpoints:
   - `GET /users` to retrieve all users.
   - `GET /users/{id}` to retrieve a user by ID.
   - `POST /users` to create a new user.
   - `PUT /users/{id}` to update an existing user.
   - `DELETE /users/{id}` to delete a user by ID.

## License

This project is licensed under the MIT License.
