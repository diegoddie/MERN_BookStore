# MERN BookStore App 🚀
This is a simple BookStore application built using the MERN (MongoDB, Express, React, Node.js) stack. It allows users to perform CRUD (Create, Read, Update, Delete) operations on books.

## Features
- View a list of books with details
- Add a new book
- Update book information
- Delete a book

## Prerequisites
- Node.js
- MongoDB Atlas account

## Getting Started
1. Clone the repo
2. Create a .env file in the root directory of the project and add your MongoDB connection URL as follows:
MONGODB_URL=your_mongodb_connection_url
Replace your_mongodb_connection_url with your actual MongoDB Atlas connection URL.
3. In both the frontend and backend directories, install the required dependencies by running ```npm i``` 
4. Run the Development Servers:
```cd frontend``` ```npm run dev```
In the other terminal, navigate to the backend directory and run:
```cd backend``` ```npm run dev```
5. Access the Application:
Open your web browser and navigate to http://localhost:5173 to access the BookStore application.

## Technologies Used
- Frontend: VITE, React, TailwindCSS
- Backend: Node.js, Express.js, AXIOS
- Database: MongoDB Atlas