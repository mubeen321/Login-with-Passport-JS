# Login with Passport.js App

This is a login with Passport.js app built with Express on the backend and React on the frontend. It allows users to log in using their Google, GitHub, or Facebook accounts using OAuth authentication. The user's session is managed using `cookie-session`, and the app utilizes Passport.js for authentication and authorization.

## Requirements

- Node.js and npm installed on your machine
- MongoDB database

## Installation

1. Clone the repository to your local machine:


2. Navigate to the project directory:


3. Install the required dependencies:


## Running the Application

To start the backend server, run the following command:

## npm run start


The backend server will be running on `http://localhost:5000`.

To start the frontend, navigate to the "client" folder and run the following command:

## npm run start



The frontend will be running on `http://localhost:3000`.

## Endpoints

- **GET /auth/login/success:** Returns the user information if the user is logged in.
- **GET /auth/login/failed:** Returns an error message if the login process fails.
- **GET /auth/logout:** Logs out the user and redirects to the home page.
- **GET /auth/google:** Initiates Google OAuth authentication.
- **GET /auth/google/callback:** Callback route for Google OAuth authentication.
- **GET /auth/github:** Initiates GitHub OAuth authentication.
- **GET /auth/github/callback:** Callback route for GitHub OAuth authentication.
- **GET /auth/facebook:** Initiates Facebook OAuth authentication.
- **GET /auth/facebook/callback:** Callback route for Facebook OAuth authentication.


