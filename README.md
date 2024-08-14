Movies API
This is a simple RESTful API for managing a collection of movies. The API is built using Go and does not utilize a database. Instead, it leverages Go's built-in data structures such as structs and slices to store and manage data in memory.

Features
Get All Movies: Retrieve a list of all movies.
Get Movie by ID: Retrieve details of a specific movie by its ID.
Create Movie: Add a new movie to the collection.
Update Movie: Update the details of an existing movie by its ID.
Delete Movie: Remove a movie from the collection by its ID.
Endpoints
GET /movies - Fetch all movies.
GET /movies/{id} - Fetch a movie by its ID.
POST /movies - Add a new movie.
PUT /movies/{id} - Update an existing movie by its ID.
DELETE /movies/{id} - Delete a movie by its ID.
Project Structure
Main Logic: The main logic for handling movie data is in the Go server.
Data Storage: Movies are stored in-memory using structs and slices.

Use a tool like Postman to test the API endpoints.
Testing
You can use Postman or any other API client to interact with the API. The following are the key endpoints you can test:

GET all movies: Send a GET request to /movies to retrieve all movies.
GET a movie by ID: Send a GET request to /movies/{id} with the movie ID.
POST a new movie: Send a POST request to /movies with the movie details in the request body.
PUT to update a movie: Send a PUT request to /movies/{id} with the updated movie details.
DELETE a movie: Send a DELETE request to /movies/{id} to remove a movie.
Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any changes.

