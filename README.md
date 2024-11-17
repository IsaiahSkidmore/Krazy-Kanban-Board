# Krazy Kanban Board

## Description
The Kanban Board is a task management application designed to help users visualize their workflow and manage tasks efficiently. This project includes user authentication, ensuring a personalized and secure experience for each user. It supports task categorization across different stages, such as **To Do**, **In Progress**, and **Done**.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [License](#license)


This application is ideal for individuals or teams seeking an organized way to track and manage tasks.

## Features
- **User Authentication:** Secure user login and account creation using JWT authentication.
- **Task Management:** Users can create, update, and delete tasks.
- **Dynamic Task Categorization:** Move tasks between "To Do," "In Progress," and "Done".
- **Responsive Design:** Optimized for use on desktop and mobile devices.


## Technologies Used
- **Front-End:** React, CSS
- **Back-End:** Node.js, Express.js
- **Authentication:** JWT (JSON Web Tokens)
- **Database:** PostgreSQL (Sequelize ORM)
- **Version Control:** Git
- **Deployment:** Render

## Setup Instructions
1. **Clone the Repository**
   ```bash
   git clone git@github.com:IsaiahSkidmore/Krazy-Kanban-Board.git
2. **Install the dependencies**
   ```bash  
   npm install
3. **Set up environment variables**
   Create a .env file in the server directory with the following variables
   ```bash
   JWT_SECRET=your_jwt_secret
   DB_NAME=your_db_name
   DB_USER=your_username
   DB_PASSWORD=your_password
4. **Seed your database**
   ```bash
   npm run seed
5. **Run the application locally**
   ```bash
   npm run start:dev
## License

This project is licensed under the MIT License 