SuppliFlex Back-End

Overview

SuppliFlex Back-End is a Node.js-based REST API server that supports supply chain management functionalities. Built with Express.js and MongoDB, this project provides secure and scalable API endpoints for managing user authentication, inventory, shipments, and order processing.


Features

User Authentication: Secure JWT-based authentication with password hashing using bcrypt.

Database Integration: Uses MongoDB with Mongoose ORM for efficient data storage and retrieval.

CORS Enabled: Allows cross-origin requests using cors middleware.

Logging & Debugging: Integrated with Morgan for request logging and dotenv for environment variable management.

Development & Linting: Supports TypeScript development with ts-node, Prettier, and ESLint.


Tech Stack

Node.js (v18+)

Express.js (v4+)

MongoDB with Mongoose

JWT Authentication

TypeScript


Installation

Prerequisites

Ensure you have the following installed:

Node.js (v18.20.6 or later)

MongoDB (local or cloud instance)


Steps

Clone the repository:

git clone https://github.com/Suppliflex/Suppliflex-Back-End.git
cd suppliflex-back-end

Install dependencies:

npm install

Create a .env file in the root directory and configure your environment variables:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Run the server:
npm start
The server will start on http://localhost:5000.


Scripts

Start the server:
npm start

Run in development mode (auto-restart on file changes):
npm run dev

Run the server with Nodemon:
nodemon server.js

Run ESLint checks:
npm run lint

Format code with Prettier:
npm run format



Development Guidelines

Follow ESLint and Prettier rules for code consistency.
Use TypeScript for type safety and maintainability.
Keep .env files and node modules out of version control.
A .gitkeep file is used to track empty directories in a Git repository. Git does not track empty folders, so adding a .gitkeep file ensures that the directory structure is preserved.


Contributing

If you'd like to contribute, please fork the repository and submit a pull request with a detailed explanation of your changes.


License

This project is licensed under the ISC License.
