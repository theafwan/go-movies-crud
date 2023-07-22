# Go Movies CRUD API
This repository contains a simple CRUD (Create, Read, Update, Delete) API implemented in Golang. The API allows you to manage movie data using in-memory structs, without any database dependencies.

### Prerequisites
Before running this project, make sure you have the following installed on your machine:

* Golang (Go) - version 1.16 or higher

### Getting Started
Follow the steps below to get the project up and running:

1. Clone the repository:
git clone https://github.com/your-username/go-movies-crud.git
2. Change into the project directory:
cd go-movies-crud
3. Run the application:
go run main.go

### Usage
Once the API is running, you can use a tool like cURL or Postman to interact with the endpoints. The API supports the following CRUD operations:

* Create: Add a new movie to the collection.
* Read: Retrieve the details of a specific movie or list all available movies.
* Update: Update the information of an existing movie.
* Delete: Remove a movie from the collection.

The API endpoints are as follows:

* GET /movies: Retrieve a list of all movies.
* GET /movies/{id}: Retrieve details of a specific movie by ID.
* POST /movies: Add a new movie to the collection.
* PUT /movies/{id}: Update the information of a movie by ID.
* DELETE /movies/{id}: Remove a movie from the collection by ID.

### Customization
You can customize the movie data or add more endpoints as per your requirements. The movie data is currently stored in-memory using Golang structs.

### Contributing
If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request. Contributions are always welcome!

### License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the terms of the license.