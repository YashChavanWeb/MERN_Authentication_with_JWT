# MERN Stack Authentication

This project is a MERN (MongoDB, Express, React, Node.js) stack application with user authentication features. It includes endpoints for signing up and signing in users, using JWT tokens for authentication.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Setup and Installation](#setup-and-installation)
- [Environment Variables](#environment-variables)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- User sign-up and sign-in
- JWT-based authentication
- Secure password hashing with bcrypt
- Responsive UI built with React

## Prerequisites

- Node.js (>= 14.x)
- MongoDB Atlas account

## Setup and Installation

1. **Clone the Repository**

   Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/mern-stack-authentication.git
   cd mern-stack-authentication
   ```

2. **Install Dependencies**

   Navigate to both the backend and frontend directories and install the necessary dependencies:

   ```bash
   # For the backend
   cd backend
   npm install

   # For the frontend
   cd ../frontend
   npm install
   ```

3. **Setup Environment Variables**

   Create a `.env` file in the `backend` directory with the following content:

   ```plaintext
   MONGO_PASSWORD= your_mongoose_password
   MONGO_USERNAME= your_mongoose_username
   MONGO_URL= your_mongoose_connection_string
   JWT_SECRET= your_jwt_secret_text
   ```

   Ensure you replace the values with your own if you are deploying this in a different environment.

4. **Database Setup**

   Ensure that your MongoDB Atlas cluster is correctly configured and accessible. You should replace the MongoDB credentials in the `.env` file with your own.

## Running the Application

1. **Start the Backend Server**

   Navigate to the `backend` directory and start the server:

   ```bash
   cd backend
   npm start
   ```

   This will start the server on the port specified in your `.env` file (default is `3000`).

2. **Start the Frontend Application**

   Open a new terminal window, navigate to the `frontend` directory, and start the React development server:

   ```bash
   cd frontend
   npm start
   ```

   The frontend application will be available at `http://localhost:3000` by default.

## Usage

- **Sign Up**: Navigate to the sign-up page of the frontend application to create a new user account.
- **Sign In**: Use the sign-in page to log in with your credentials.
- **Logout**: Once logged in, you can log out using the logout button.

## Contributing

Feel free to contribute to this project by submitting pull requests or opening issues. Please ensure that your contributions adhere to the project’s coding standards and conventions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Note**: Be careful with sensitive information such as API keys and credentials. Never expose them in public repositories or logs. Always use environment variables to manage such information securely.

### Key Points:

1. **Clone the repository**: Guides the user to clone the project and navigate to it.
2. **Install dependencies**: Instructions for installing both backend and frontend dependencies.
3. **Environment variables**: Details how to set up environment variables and explains their purpose.
4. **Run the application**: Step-by-step instructions to start both the backend and frontend.
5. **Usage**: Basic usage instructions for signing up, signing in, and logging out.
6. **Contributing and License**: Information on how to contribute and the licensing of the project.
