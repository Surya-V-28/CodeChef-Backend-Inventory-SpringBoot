# Movie Backend Application - Spring Boot (CodeChef)

This Spring Boot project demonstrates secured CRUD operations with JWT authentication, pagination, sorting, and Dockerization.

## Features
- **CRUD Operations (Movies):** All endpoints are secured with JWT.
- **JWT Authentication:** Secures movie endpoints.
- **Pagination & Sorting:** Manage large movie collections efficiently.
- **Dockerized:** Ready for containerized deployment.
- **Rate Limiting:** IP-based request control.
- **API Testing:** Tested with Spring Security.

## Bonus Features Implemented
✔ Dockerization  
✔ IP-based Rate Limiting  
✔ Pagination with Sorting

## Project Structure
- **controller:** API endpoints.
- **service:** Business logic.
- **repository:** Database operations.
- **model:** Movie data models.
- **security:** JWT management.
- **exception:** Custom error handling.

## API Endpoints
### Authentication
- `POST /api/auth/login` - Obtain JWT token.
- `POST /api/auth/register` - Register user.
- `POST /api/auth/forgot-password` - Request password reset.
- `POST /api/auth/reset-password` - Reset password.

### Movie CRUD Operations (Secured)
- `GET /api/v1/movie/{id}` - Retrieve movie by ID.
- `POST /api/v1/movie` - Create a movie.
- `PUT /api/v1/movie/{id}` - Update a movie.
- `DELETE /api/v1/movie/{id}` - Delete a movie.
- `GET /api/v1/movie/getAllMoviePage` - Get movies with pagination.
- `GET /api/v1/movie/getAllMoviePageSort` - Get movies with pagination and sorting.

## Images
[View Project Images](https://github.com/Surya-V-28/CodeChef-Backend-Inventory-SpringBoot/blob/main/ReadMeImages/imaages.pdf)

## Docker Compose Command
```bash
docker-compose up --build
```

