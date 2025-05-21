# Secrets Project

A simple API project for securely managing and sharing secrets. Built as part of the Full Stack Development Resources.

## Features

- User authentication and authorization
- Secure storage of secrets
- RESTful API endpoints
- Environment-based configuration

## Technologies Used

- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT for authentication

## Getting Started

1. **Clone the repository:**
    ```bash
    git clone <repository-url>
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Set up environment variables:**
    - Create a `.env` file with your MongoDB URI and JWT secret.

4. **Run the server:**
    ```bash
    npm start
    ```

## API Endpoints

- `POST /register` - Register a new user
- `POST /login` - Authenticate user and receive token
- `GET /secrets` - Retrieve secrets (protected)
- `POST /secrets` - Add a new secret (protected)

## License

This project is for educational purposes.