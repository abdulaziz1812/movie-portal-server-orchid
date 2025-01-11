# Movie Portal Server - ScreenBox API

This is the backend server for **ScreenBox**, a movie portal that allows users to add, explore, manage, and save their favorite movies. This server handles movie data management, including CRUD operations for movies and user favorite movies.

## Live API URL

While this is the backend API, you can connect it to your frontend (React app). The server is running at:


## Features

- **Movies API**:
  - Retrieve all movies: `GET /movies`
  - Retrieve featured movies (top-rated): `GET /featured-movies`
  - Retrieve a specific movie by ID: `GET /movies/:id`
  - Add a new movie: `POST /movies`
  - Update an existing movie: `PUT /movies/:id`
  - Delete a movie: `DELETE /movies/:id`

- **Favorites API**:
  - Add a movie to the favorites list: `POST /favorites`
  - Retrieve all favorite movies for a user: `GET /favorites?email=<user_email>`
  - Remove a movie from favorites: `DELETE /favorites/:id`


