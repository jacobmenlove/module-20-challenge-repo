# module-20-challenge-repo

Coding Quiz Application

# Description
The Coding Quiz Application is a full-stack web application designed to provide users with a fun and interactive way to test their programming knowledge through a series of quiz questions. The application leverages React for the front end and Node.js with MongoDB for the back end, providing a seamless experience for users.

# Table of Contents
Features
Technologies Used
Installation
Usage
Environment Variables
Deployment
Contributing
License
Acknowledgments

# Features
Interactive Quiz: Users can answer multiple-choice questions to test their programming knowledge.
Real-time Score Tracking: User scores are calculated in real-time and displayed at the end of the quiz.
Responsive Design: The application is fully responsive and works seamlessly on various devices.
User Authentication: Users can sign up and log in to track their quiz results.
Admin Panel: Admin users can add, edit, and delete quiz questions from the database.

# Technologies Used
Frontend:
React
Vite
CSS
Backend:
Node.js
Express
MongoDB (using Mongoose)
Testing:
Cypress
Deployment:
Render
Version Control:
GitHub

# Installation

To run the project locally, follow these steps:

Clone the repository:

bash

git clone https://github.com/jacobmenlove/module-20-challenge-repo.git
cd module-20-challenge-repo
Install dependencies for both server and client:

bash

cd server
npm install
cd ../client
npm install
Create a .env file in the server directory and add your MongoDB connection string:

bash

MONGODB_URI=mongodb://localhost:27017/your_local_db_name
Run the application:

# Start the server:

bash 

cd server
npm start
Start the client:

bash

cd client
npm run dev

# Usage
Access the application in your web browser at http://localhost:3000 (or the port configured for your client).
Sign up or log in to track your quiz results.
Start the quiz and test your programming knowledge!
Environment Variables
Make sure to set the following environment variable in your .env file for the server:

MONGODB_URI: mongodb+srv://jacobmenlove:fwEWq4drMfjT5MQc@challenge-20.v2vn1.mongodb.net/?retryWrites=true&w=majority&appName=Challenge-20


# Deployment
The application is deployed on Render. You can access the live application here: https://module-20-challenge-repo.onrender.com

# Contributing
Contributions are welcome! If you would like to contribute, please follow these steps:

Fork the repository.
Create a new branch:

bash
Copy code
git checkout -b feature/YourFeature
Make your changes and commit them:

bash
Copy code
git commit -m "Add some feature"
Push to the branch:

bash
Copy code
git push origin feature/YourFeature
Create a pull request.


Acknowledgments
Thanks to MongoDB for their excellent database solution.
Thanks to Render for providing a reliable deployment platform.
Special thanks to Cypress for their powerful testing framework.
