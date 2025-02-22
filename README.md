# MongoFinal

![MongoDB](https://img.shields.io/badge/MongoDB-Database-green)
![Node.js](https://img.shields.io/badge/Node.js-JavaScript-green)
![Express](https://img.shields.io/badge/Express-Framework-lightgrey)
![License](https://img.shields.io/badge/License-MIT-blue)

Welcome to **MongoFinal**, an elegant and robust application built with MongoDB, Node.js, and Express. This project serves as a final demonstration of integrating MongoDB with a Node.js backend using the Express framework.

## 🚀 Features

- **CRUD Operations**: Full Create, Read, Update, and Delete functionality.
- **RESTful API**: Well-structured and RESTful endpoints.
- **Error Handling**: Comprehensive error handling and validation.
- **Modular Codebase**: Clean and modular architecture for scalability.
- **Environment Configuration**: Secure and configurable environment settings.

## 📂 Project Structure

```
mongofinal/
├── models/
│   └── userModel.js
├── routes/
│   └── userRoutes.js
├── controllers/
│   └── userController.js
├── config/
│   └── dbConfig.js
├── middleware/
│   └── authMiddleware.js
├── utils/
│   └── errorHandler.js
├── .env
├── package.json
├── server.js
└── README.md
```

## 🛠️ Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/KadzhanT/mongofinal.git
   cd mongofinal
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the following:
   ```env
   MONGO_URI=your_mongodb_connection_string
   PORT=5000
   ```

4. **Run the application:**
   ```sh
   npm start
   ```

## 📋 API Endpoints

- **GET /api/users**: Retrieve all users
- **POST /api/users**: Create a new user
- **GET /api/users/:id**: Retrieve a user by ID
- **PUT /api/users/:id**: Update a user by ID
- **DELETE /api/users/:id**: Delete a user by ID

## 👨‍💻 Code Overview

### `models/userModel.js`
Defines the schema and model for user data.

### `routes/userRoutes.js`
Contains all the user-related routes.

### `controllers/userController.js`
Handles the logic for user-related operations.

### `config/dbConfig.js`
Manages the MongoDB connection configuration.

### `middleware/authMiddleware.js`
Includes authentication and authorization middleware.

### `utils/errorHandler.js`
Centralized error handling utility.

### `server.js`
The main entry point of the application, where the server is configured and started.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to check the [issues page](https://github.com/KadzhanT/mongofinal/issues).


