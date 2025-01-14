# GOLang CRUD Application 
  This project is a simple CRUD (Create, Read, Update, Delete) application.
  Built with GOLang and the Gorilla MUX package.
  The application manages movie records and demonstrates the use of RESTful APIs.

## Features
- **Create** a new movie record
- **Read** all movies or a specific movie by ID
- **Update** an existing movie record
- **Delete** a movie record

## Tools & Technologies
- **Programming Language**: GoLang
- **Framework**: Gorilla Mux for routing
- **Testing**: Postman
- **Port**: 8080

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/maxwell-alan-joseph/Go-CRUD-application
2. Navigate to the project directory:
   ```bash
   cd GoLang-CRUD-App
3. Install dependencies:
   ```bash
    go mod tidy
4. Run The Application:
   ```bash
   go run main.go
5. Use Postman to test the endpoints:
   
  - GET /movies - Retrieve all movies
  - GET /movies/{id} - Retrieve a movie by ID
  - POST /movies - Add a new movie (include JSON body)
  - PUT /movies/{id} - Update a movie (include JSON body)
  - DELETE /movies/{id} - Delete a movie by ID

## EndPoints

| HTTP Method | Endpoint         | Description                |
|-------------|------------------|----------------------------|
| GET         | `/movies`        | Retrieve all movies        |
| GET         | `/movies/{id}`   | Retrieve a movie by ID     |
| POST        | `/movies`        | Create a new movie         |
| PUT         | `/movies/{id}`   | Update a movie             |
| DELETE      | `/movies/{id}`   | Delete a movie             |

## Architecture
  The Project follows a simple architecture:
  - Routes: Define API endpoints
  - Functions: Implement CRUD operations
  - Database: In-memory slice of movies (no persistent database used)
  - Postman: Used for testing the APIs.
    
[Architecture Diagram](./assets/GO-CRUD-application.drawio.png)

## Future Enhancements
- Integrate a database (e.g., MySQL, PostgreSQL)
- Add user authentication
- Improve error Handling and logging 




