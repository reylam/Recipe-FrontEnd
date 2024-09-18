# Recipe App

A **Recipe App** built with Laravel (Backend) and React or Flutter (Frontend). This app allows users to register, log in, add recipes, view all recipes, and manage their profiles. It also includes features for comments, ratings, and more.

## Features

- **Authentication** (Register & Login)
- **User Profiles**: View and edit your profile
- **Add Recipe**: Add new recipes with images, ingredients, and instructions
- **See All Recipes**: Browse and search all available recipes
- **Recipe Details**: View recipe details, including ingredients, steps, comments, and ratings
- **Comments and Ratings**: Users can leave comments and rate recipes
- **Favorite Recipes**: Save recipes to your favorites list

## Technologies Used

- **Backend**: Laravel (PHP Framework)
- **Frontend**: React or Flutter
- **Database**: MySQL / SQLite
- **Authentication**: Laravel Sanctum or JWT
- **Storage**: Laravel Filesystem (for images)

## API Endpoints

### Authentication
- `POST /api/register`: Register a new user
- `POST /api/login`: Log in a user
- `POST /api/logout`: Log out the current user

### User Profile
- `GET /api/user/profile`: Get the user's profile information
- `PUT /api/user/profile`: Update the user's profile

### Recipes
- `GET /api/recipes`: Get all recipes
- `POST /api/recipes`: Add a new recipe (authenticated users only)
- `GET /api/recipes/{id}`: Get recipe details by ID
- `PUT /api/recipes/{id}`: Update a recipe (recipe owner only)
- `DELETE /api/recipes/{id}`: Delete a recipe (recipe owner only)

### Comments & Ratings
- `POST /api/recipes/{id}/comments`: Add a comment to a recipe
- `POST /api/recipes/{id}/ratings`: Rate a recipe

## Installation

**Clone the repository**:
   ```bash
   git clone https://github.com/username/recipe-app.git
   cd recipe-app
