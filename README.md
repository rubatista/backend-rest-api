# 🚀 Backend REST API

A robust and scalable REST API built with Node.js, Express, and TypeScript, using MongoDB as the database.

## 📖 Table of Contents
- [📝 Description](#-description)
- [✨ Features](#-features)
- [⚙️ Requirements](#️-requirements)
- [📥 Installation](#-installation)
- [📚 API Documentation](#-api-documentation)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

## 📝 Description

This repository contains a REST API built with modern web development technologies. It is designed to handle CRUD operations, user authentication, and more. The backend is implemented using:
- **Node.js** and **Express** for the server.
- **TypeScript** for type safety and maintainability.
- **MongoDB** as the database.

## ✨ Features
- 🌐 RESTful API with CRUD operations for resources.
- 🔒 User authentication and authorization (e.g., JWT).
- 🛠️ Centralized error handling and logging.
- 📦 MongoDB integration.
- 📘 Built with TypeScript for better code quality.

## ⚙️ Requirements
- **Node.js** >= 16.x
- **npm** >= 8.x or **Yarn** >= 1.x
- **MongoDB** (local or cloud instance)

## 📥 Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/rubatista/backend-rest-api.git
   cd backend-rest-api
   ````

2. Install dependencies:
   ```bash
   npm install
   ````

3. Start the development server:
   ```bash
   npm start
   ````

Access the API at http://localhost:3000 (or your configured port). You can use tools like Postman or cURL to test the endpoints.


## 📚 API Documentation

Here are some example endpoints provided by the REST API:

    POST /auth/register - Create a new user.
    POST /auth/login - Login user.
    GET /users - Fetch all resources.
    PATCH /users/:id/update - Update a user by ID.
    DELETE /users/:id/delete - Delete a user by ID.


## 🤝 Contributing

Contributions are welcome! To contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature-name
   ````
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ````
4. Push to your branch:
   ```bash
   git push origin feature-name
   ````
5. Open a Pull Request on GitHub and provide a description of your changes.